---
날짜: '"2023-10-31"'
넘버: 
태그: 
출처: https://medium.com/@saschagrunert/demystifying-containers-part-i-kernel-space-2c53d6979504
aliases:
---
### 날짜  2023-10-31 18:05

### 태그:

>[!메모]
>

### 원문
---
# Namespace
- 2002년 2.4.19에 도입된 리눅스 커널 기능
- 특정 전역 시스템 리소스를 추상화 계층으로 감싸는 기능.
	- 서로 다른 프로세스 그룹이 시스템에 대해 서로 다른 시스템 환경을 가질 수 있도록 한다.
- 컨테이너는 2013년 3.8 버전에서 사용자 네임스페이스의 도입과 함께 완성되었다.
- 현재 구현된 네임스페이스
	- mnt, pid, net, ipc, uts, user, cgroup 7가지 이다.
## API
- 리눅스 커널의 네임스페이스는 3개의 주요 시스템콜로 이루어져 있다.
### clone
- clone은 fork와 유사한 방식으로 새로운 자식 프로세스를 생성한다.
- clone API는 자식 프로세스가 메모리 공간, fd 테이블, 시그널 핸들러 테이블과 같은 실행 컨텍스트의 일부를 호출 프로세스를 위한 새 네임스페이스를 생성할 수 있다.
![[Pasted image 20231031182926.png]]
### unshare
- 프로세스가 현재 다른 프로세스와 공유 중인 실행 컨텍스트의 연결을 해제할 수 있음.
![[Pasted image 20231031183742.png]]
### setns
- 호출 스레드를 제공된 네임스페이스 파일 기술자와 재연결한다. 이 함수는 기존 네임스페이스에 join 하는 데 사용할 수 있다.
![[Pasted image 20231101165451.png]]
### proc
- `proc` 파일 시스템은 추가 네임스페이스 관련 파일을 채운다.
- Linux 3.8부터 `/proc/$PID/ns`의 각 파일은 참조된 네임스페이스에 대한 연산을 수행하기 위한 핸들로 사용할 수 있는 "magic" 링크이다.
```bash
> ls -Gg /proc/self/ns/  
total 0  
lrwxrwxrwx 1 0 Feb 6 18:32 cgroup -> 'cgroup:[4026531835]'  
lrwxrwxrwx 1 0 Feb 6 18:32 ipc -> 'ipc:[4026531839]'  
lrwxrwxrwx 1 0 Feb 6 18:32 mnt -> 'mnt:[4026531840]'  
lrwxrwxrwx 1 0 Feb 6 18:32 net -> 'net:[4026532008]'  
lrwxrwxrwx 1 0 Feb 6 18:32 pid -> 'pid:[4026531836]'  
lrwxrwxrwx 1 0 Feb 6 18:32 pid_for_children -> 'pid:[4026531836]'  
lrwxrwxrwx 1 0 Feb 6 18:32 user -> 'user:[4026531837]'  
lrwxrwxrwx 1 0 Feb 6 18:32 uts -> 'uts:[4026531838]'
```
- 이를 통해 특정 프로세스가 어느 네임스페이스에 있는지 추적할 수 있다.
- `util-linux`라는 패키지를 이용하여 네임스페이스를 다룰 수 있다.
	- 시스템 호출을 내부적으로 사용하는 `lsns`툴을 사용한다.
	- 이 도구는 액세스 가능한 모든 네임스페이스 또는 지정한 네임스페이스에 대한 유용한 정보를 나열한다.
## Available Namespaces
### Mount(mnt)
- mnt 네임스페이스는 2002년에 처음 구현되었다.
- 리눅스는 mnt 네임스페이스를 사용하여 프로세스 그룹별로 mount point set를 격리시킬 수 있었다.
- chroot 보다 더 안전한 방식으로 환경을 구성할 수 있음.
- 사용 사례
	- API 함수 호출 또는 공유 해제 명령줄 도구를 통해 수행할 수 있음.
```bash 
$> sudo unshare -m
#> mkdir mount-dir
#> mount -n -o size=10m -t tmpfs tmpfs mount-dir
#> df mount-dir
Filesystem 1K-blocks Used Avaliable Use% Mounted on
tmpfs          10240    0     10240   0% <PATH>/mount-dir
#> touch mount-dir/{0,1,2}
```
- 호스트 시스템 수준에서는 사용할 수 없는 tmpfs를 마운트 하였다.
```bash
$> ls mount-dir
$> grep mount-dir /proc/mounts
$>
```
- 마운트 지점에 사용되는 실제 메모리는 커널의 일부이며 다른 모든 파일시스템의 기반이 되는 VFS(가상 파일시스템)이라는 추상화 계층에 있다.
- 네임스페이스가 파괴되면 마운트 메모리는 복구할 수 없게 손실된다.
- 마운트 네임스페이스 추상화를 사용하면 루트 권한이 없어도 루트 사용자로 전체 가상환경을 만들 수 있다.
- 호스트 시스템에서는 proc 파일 시스템 내부의 마운트 정보 파일을 통해 마운트 지점을 확인할 수 있다.
```bash
> grep mount-dir /proc/$(pgrep -u root bash)/mountinfo  
349 399 0:84 / /mount-dir rw,relatime - tmpfs tmpfs rw,size=1024k
```

## -> 나중에 필요할 때 정리하도록 하자..

---
### 생각(파생된 질문/생각)

### 출처
- https://medium.com/@saschagrunert/demystifying-containers-part-i-kernel-space-2c53d6979504
### 연결 문서 (연결 이유)
