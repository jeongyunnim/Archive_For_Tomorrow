---
날짜: '"2023-10-26"'
넘버: 
태그: 프로그래밍/도커
출처: https://medium.com/@saschagrunert/demystifying-containers-part-i-kernel-space-2c53d6979504
aliases:
---
### 날짜  2023-10-26 02:50

### 태그:

>[!메모]
>

### 원문
---
- UNIX OS는 현재 실행 중인 프로세스의 루트 디렉토리를 바꿀 수 있는 기능이 있다.
- Berkeley Software Distribution(BSD)으로 이어나가고 있는 UNIX version 7(1979)의 chroot으로 부터 기원한다.
- [[mcroservicees]]
- Chroot의 사용
```bash
> mkdir -p new-root/{bin,lib64}
> cp /bin/bash new-root/bin
> cp /lib64/{ld-linux-x86-64.so*,libdl.so.2,libreadline.so*,libtinfo.so*} new-root/lib64  
> sudo chroot new-root}
```
- 새로운 루트 디렉토리를 만들었다. bash 쉘과 종속 파일을 복사하고 chroot를 실행했다.
- 이 jail 만으로는 bash와 빌트인 명령만 사용할 수 있을뿐이다.
![[Pasted image 20231027113931.png]]
> One might think it could be worth running a statically linked binary in a jail and that would be the same as running a container image. It’s absolutely not, and a jail is not really a standalone security feature but more a good addition to our container world.

- 이 독립적인 공간 안에서 바이너리를 정적으로 링크하고 실행하는 것과 컨테이너 이미지를 실행하는 것과 같다고 생각할 수 있다.
	- 절대 아님.
	- 이 독립적인 공간은 완전히 독립적인 보안기능을 가지고 있지 않다. 그러나 우리의 컨테이너 세상에서 누릴 수 있는 추가적인 요소들이 있다.
- 시스템 콜을 호출한 현재 작업 폴더가 바뀐 것이아니다.
	- 새로운 root의 바깥을 상대 경로로 접근할 수 있다.
```c++
#include <sys/stat.h>
#include <unistd.h>

int main(void)
{
	mkdir(".out", 0755);
	chroot(".out");
	chdir("../../../../");
	chrot(".");
	return execl("/bin/bash", "-i", NULL);
}
```
- 현재 chroot는 container runtime에 사용되지 않는다.
	- pivot_root로 대체되었음.
- 더 유용하게 독립된 환경을 구성하기 위해서는 적절한 루트 파일 시스템(rootfs)이 필요하다.
	- 모든 바이너리, 라이브러리 및 필요한 파일 구조가 포함된다.
		- 이미 존재하는 Open Container Initiative의 껍질을 벗겨보는 것은 어떨까?
		- [skopeo](https://github.com/containers/skopeo)와 [umoci](https://github.com/openSUSE/umoci)라는 도구로 해결할 수 있다.
```bash
$> skopeo copy cdocker://opensuse/tumbleweed:latest
oci:tumbleweed:latest
[output removed]
$> sudo umoci unpack --image tumleweed:latest bundle
[output removed]
$> sudo chroot bundle/roofs
#>
```
- 이렇게 추출한 루트 파일 시스템으로부터 chroot를 실행하여 독립 환경으로 진입한다.
- 모든 것이 작동하는 것 같지만, 프로세스 관점에서 보면 독립 환경 외부를 들여다 볼 수 있다는 문제가 있다.
```bash
$> mkdir /proc
$> mount -t proc porc /proc
$> ps aux
[output removed]
```
- 

- old mount
- 
---
### 생각(파생된 질문/생각)

### 출처
- https://medium.com/@saschagrunert/demystifying-containers-part-i-kernel-space-2c53d6979504
### 연결 문서 (연결 이유)
