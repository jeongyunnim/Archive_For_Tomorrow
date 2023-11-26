---

excalidraw-plugin: parsed
tags: [excalidraw]

---
==⚠  Switch to EXCALIDRAW VIEW in the MORE OPTIONS menu of this document. ⚠==


# Text Elements
Docker ^THqd4k6g

Process + Task ^upLMyaGc

Program ^KkcCYDx5

PID ^KwTkIBp0

작업의 단위 ^rn79ywZ5

process -> OS가 자원을 관리하는 단위.
program -> Routine, Procedure 이라고 불리는 명령어의 집합을 처리 일련의 연산을 수행하는 주체 ^V1lGIYxe

User
Kernel ^UaRCjDDA

S/W
H/W ^bnkPpsZI

CPU
core ^gdYgehmg

0 ^08Vb3B2n

1 ^PDhFkfr0

2 ^HTwjdNag

3 ^0t0gcBlf

OS ^l2NnNpvf

자원 관리 + I/O ^xNH4aHl0

PID
1000 ^r52SRCPH

PID
1001 ^x9rLlIky

+  ^Bc0Wm0Oe

||||||||||||||||||||||||||| ^asl1Ifvf

RAM ^gxyGPwlQ

PID 1000이 할당받은 영역을 벗어난다면 
PID 1001에 데이터가 씌워질 수 있음.
OS가 이런 일이 일어나지 않도록 막아준다.
 ^Le16jlY0

PID
2000 ^0KVOjj9O

container:  ^hY0O2Jie

커널과 H/W는 공유
Host OS 입장에서 보면 
Docker 또한 프로세스로 관리가 된다.
 ^vO1aHkXk

가상화 ^b2tUclJH

User
Kernel ^ETjP3eDJ

S/W
H/W ^jZYuSgpv

process ^vOHbpFom

file ^TCOwTU8k

구성요소 ^0qoLnarC

driver ^6E1v3UXM

CPU ^5YOlD0Yt

+ ^8CMjTxXe

RAM ^njr7x9dv

+ ^sFj4mngX

HDD ^8mGnH6Yo

core ^8osMrjTV

자신만의 고유한 메모리를 보장 받는다.  ^qDExiQuE

== virtual memory
process마다 독립적인 공간이다. ^O87Gj7sH

MS-Word
#1 ^tq0J1WQH

virtual memory ^uzdn8Bcv

가상메모리: 램을 이야기하는 것이지만
2차 메모리(HDD)를 포함해서 virtual memory라고 하자. ^7JcvmDBH

MS-Word
#2 ^SqWX0sQZ

멀티태스킹 환경에서는 각각의 프로세스가 가상메모리라는 체계를 활용하고 있다. ^UXqozoZG

User
Kernel ^Sxikb3bF

S/W
H/W ^5tjdZqfg

가상 머신 ^DECbSRZS

TCP/IP ^allNpC3v

driver ^fdMCbK07

NIC ^09xemSwa

process ^pc1aVbNM

file ^K4Sibamq

socket ^EXGIvJDF

VMware ^zIExxQLw

VMware ^a0oDntb3

VMware ^TbH69g8F

TCP/IP ^QufTEwS0

driver ^BmduPOZ6

NIC ^2hLh5SxK

process ^I9StjEoo

file ^7jdRyok8

socket ^dHbVYVGA

Linux #1 ^lKyWESJt

Linux #2 ^aYMe5k6f

Linux #3 ^cwSPrBwu

U
K ^KhxmL1kB

S/W
H/W ^UMRuPxzt

TCP/IP ^yHR6Ms9k

driver ^kc1HKtIa

NIC ^5dDTeVbu

process ^jQRB7zHA

file ^PXUKW4Sw

socket ^q7zMgN7i

U
K ^2BHqKM1m

S/W
H/W ^HzqEcJDf

TCP/IP ^FFejlAGg

driver ^uapq01B3

NIC ^qySRzfm5

process ^pNI5DcYe

file ^uvFJqCBO

socket ^ecZM5yYR

U
K ^gUtjDbFQ

S/W
H/W ^5SneuPIj

S/W NIC
virtual NIC driver ^alsYyXDN

Host OS ^Qt4R7NWi

Guest OS ^qysbl5Kr

이 virtual NIC을 L2 switch처럼 사용한다. ^XekcCLy3

internet ^xVAYoLM3

NAT(Network Address Translation) 기능 지원(공유기) ^SCdUY91x

도커를 사용하는 이유.
 ^3LneMCjA

User
Kernel ^EJol7a69

S/W
H/W ^V6HFMPQK

TCP/IP ^ogw24fkS

driver ^6apG3K9Q

NIC ^glIYNbaO

Linux #1 ^GDZXWgMC

Linux #2 ^3b6rNCFG

process ^qTUY1kL4

file ^QkWAkxsh

사용 중인 프로세스 ^07FSKEvb

1 ^qLrh0dQB

2 ^Nbvm7uNb

3 ^HZNEkPXT

4 ^aLmHV2dH

5 ^kyLr6Kfj

6 ^UlLBeCjz

7 ^6yrAxyfw

8 ^thEL5kk8

8개나 되는 프로세스 중, 요놈들은 꼭 필요한가? ^oHlAJ0BV

[[쿠버네티스|쿠버네티스]]
 ^IIcthEKq

출처: https://kubernetes.io/ko/docs/concepts/overview/ ^tDVObzfZ

User
Kernel ^tehsIeFQ

S/W
H/W ^QAStuCMg

OS: Linux ^i8MSAe21

컨테이너 이미지 저장소 ^VGoIzV7u

개발 환경 ^uFgOPfOT

서버

 ^9b6caVYq

서버

 ^xxr8gurs

서버

 ^mYyxAIog

Road 
balancer ^UBQybXu5

사용자 ^aW0Fy5JH

개발자 ^ceeGdHKt

이미지
업로드 ^77SKHQNe

배포 ^hcYqJUg5

컨테이너만으로 배포한다면 모든 과정을 수동으로 처리해야 함. ^IRAEh0ev

쿠버네티스 클러스터 ^y8OsAhjI

마스터 ^YVK2ZMzT

kube-apiserver ^BanCZrTO

인그레스 ^UkSGEpJ6

인그레스 노드 ^u8G9gjbY

인그레스
컨트롤러 ^yAv6QMVL

nginx ^0iyoJJ1D

서비스 ^P1X4Aqjx

노드 ^gryp126b

피드 ^8fr6gYs0

피드 ^pFrE1jho

노드 ^Yy6neeqM

피드 ^XKN5fyi8

장애 발생 ^1HzLnpNV

bin

home     me 

usr

var ^5BtDYdp6

test


work ^e6ZNbbDn

bin
usr
var ^UGQV08on

\ ^wPjoA1Pv

jail ^lXrmn7zG

chroot ^U62GSmr4

워드프레스 ^4PyXeiMC

워드프레스(본체)
아파치
PHP 런타임


MySQL ^mU3dGRbB

워드프레스 컨테이너 ^pTzeYQff

MySQL
컨테이너 ^ecxbFovw

sender ^4dcxyexb

recipient ^jbDMTqgs

public key ^CKxnv7Px

private key ^mClRuRJW

암호화 ^h36ZvW6V

복호화 ^xcJjrVDC

유일한 pair ^azd6fyzH

보내는 이 ^olKQEyJ5

 ^CGyeqbPt

받는 이 ^ERvPZNgU

해커 ^SoITUkQB

public
private ^l867T5jL

정보를 탈취해도
풀 수 있는 방법이 없음 ^t8TH9sxv

Namespace - PID ^QCBkVQBQ

PID 1 ^ZIZH9zBm

Child System(Container) ^eJn9s7LN

PID 1 ^WGcnm42n

PID 2 ^z2AC2gNt

PID 1 ^d9JIARnv

PID 1 ^W3n5wfvx

PID 1 ^PZxEE8Im

PID 1 ^LzmDu4ZG

GET / ^FQLONdx6

요청 처리
/index.html ^uEz633SZ

200 OK
/index.html ^BTIA36tE

GET / ^lRQbB1H0

요청 전처리
URL 재작성, 내부 목적지 전환 ^twAdz7ux

200 OK
/index.html ^vrAPh6PF

[웹서버]
엔진엑스/아파치.. ^v6s6kUio

[클라이언트]
chrome, firefox.. ^tQxh5KfF

[애플리케이션]
PHP, 파이썬.. ^E9mr608p

요청 전달
CGI를 사용한 통신 ^DT5Km479

응답 반환
CGI를 사용한 통신 ^72mdNxwK

요청 처리
스크립트
실행 ^AGkGdbFH

응답 후처리
gzip 압축
문자 인코딩 ^KWceMxoX

클라이언트 ^h1Z7BTtI

G ^nHfE4Bht

애플리케이션 ^CUqTje0W

프로세스 관리 ^VohtJIvQ

PHP-FPM ^HLTmfRi2

PHP ^yccaS9uw

웹 서버 ^xuoRwole

NGINX ^EQxOzjek

WordPress
+ PHP ^W1RJ3MCf

MySQL ^ASzwZ4Wf


# Embedded files
c6c86de84d2fa95cc04b57a4c2191bbbbc7dd6c2: https://kubernetes.io/images/docs/Container_Evolution.svg

%%
# Drawing
```json
{
	"type": "excalidraw",
	"version": 2,
	"source": "https://github.com/zsviczian/obsidian-excalidraw-plugin/releases/tag/1.9.8",
	"elements": [
		{
			"type": "rectangle",
			"version": 142,
			"versionNonce": 739654338,
			"isDeleted": false,
			"id": "bX1Dhuo3hIU1ZRPUgtMHx",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2214.8808722969884,
			"y": 523.3181829623456,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 867.6109245262955,
			"height": 341.39579741638727,
			"seed": 28531753,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029724,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 166,
			"versionNonce": 1938901598,
			"isDeleted": false,
			"id": "uL2MJpxauqPt5Mm4UG2IZ",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2642.8737060858098,
			"y": 487.290543404039,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffffff",
			"width": 278.04476285295004,
			"height": 152.5689476111463,
			"seed": 1433420041,
			"groupIds": [
				"0gPaKiLeAW35tFsntU8mX"
			],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [],
			"updated": 1700563029724,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 130,
			"versionNonce": 1086689922,
			"isDeleted": false,
			"id": "7rCt97yhdjw82vBYq9270",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2679.07347281542,
			"y": 553.5593107867312,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffffff",
			"width": 218.57911681410178,
			"height": 68.03121343843657,
			"seed": 447302951,
			"groupIds": [
				"0gPaKiLeAW35tFsntU8mX"
			],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"id": "DDFALHs8v6U0AXOa5bSVO",
					"type": "arrow"
				}
			],
			"updated": 1700563029724,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 176,
			"versionNonce": 1173638814,
			"isDeleted": false,
			"id": "THqd4k6g",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -450.9981423816174,
			"y": -514.9965965895257,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 230.765625,
			"height": 78.77581521739127,
			"seed": 958852509,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029724,
			"link": null,
			"locked": false,
			"fontSize": 65.6465126811594,
			"fontFamily": 3,
			"text": "Docker",
			"rawText": "Docker",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Docker",
			"lineHeight": 1.2,
			"baseline": 63
		},
		{
			"type": "text",
			"version": 205,
			"versionNonce": 2100556354,
			"isDeleted": false,
			"id": "upLMyaGc",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -312.7190749284485,
			"y": -281.98757882892846,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 164.0625,
			"height": 24,
			"seed": 558470045,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "no7w8bjJgXqRL0Yv-ub1X",
					"type": "arrow"
				},
				{
					"id": "TzGMILq26d4heScr2Fo_Y",
					"type": "arrow"
				}
			],
			"updated": 1700563029724,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 3,
			"text": "Process + Task",
			"rawText": "Process + Task",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Process + Task",
			"lineHeight": 1.2,
			"baseline": 20
		},
		{
			"type": "text",
			"version": 350,
			"versionNonce": 367839966,
			"isDeleted": false,
			"id": "KkcCYDx5",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -439.31849899376834,
			"y": -281.98757882892846,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 82.03125,
			"height": 24,
			"seed": 582916211,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "TzGMILq26d4heScr2Fo_Y",
					"type": "arrow"
				}
			],
			"updated": 1700563029724,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 3,
			"text": "Program",
			"rawText": "Program",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Program",
			"lineHeight": 1.2,
			"baseline": 20
		},
		{
			"type": "text",
			"version": 451,
			"versionNonce": 608197122,
			"isDeleted": false,
			"id": "KwTkIBp0",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -295.0401932305281,
			"y": -366.1028294170708,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 35.15625,
			"height": 24,
			"seed": 1795389821,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029724,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 3,
			"text": "PID",
			"rawText": "PID",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "PID",
			"lineHeight": 1.2,
			"baseline": 20
		},
		{
			"type": "arrow",
			"version": 215,
			"versionNonce": 34324254,
			"isDeleted": false,
			"id": "no7w8bjJgXqRL0Yv-ub1X",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -176.2888850164867,
			"y": -288.3393560746231,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 80.09514562833459,
			"height": 65.68896674053497,
			"seed": 1342782835,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1700563029724,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "upLMyaGc",
				"focus": 0.6307531780434225,
				"gap": 5.651776848898805
			},
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					6.714362904921927,
					-63.722944926813
				],
				[
					80.09514562833459,
					-65.68896674053497
				]
			]
		},
		{
			"type": "text",
			"version": 124,
			"versionNonce": 1156172226,
			"isDeleted": false,
			"id": "rn79ywZ5",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -79.66737627011946,
			"y": -367.4147378711926,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 96.49993896484375,
			"height": 25,
			"seed": 2110940819,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029724,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "작업의 단위",
			"rawText": "작업의 단위",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "작업의 단위",
			"lineHeight": 1.25,
			"baseline": 18
		},
		{
			"type": "arrow",
			"version": 302,
			"versionNonce": 784477022,
			"isDeleted": false,
			"id": "TzGMILq26d4heScr2Fo_Y",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -393.8591908541543,
			"y": -244.73944492633734,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 125.32492265025166,
			"height": 41.00852474488653,
			"seed": 621492627,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1700563029724,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "KkcCYDx5",
				"focus": 0.15421309263899596,
				"gap": 12.548133505795306
			},
			"endBinding": {
				"elementId": "upLMyaGc",
				"focus": 0.3745120762393534,
				"gap": 6.060084550327247
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					15.71395740988305,
					33.12047499582684
				],
				[
					112.64411346347862,
					32.25453762780825
				],
				[
					125.32492265025166,
					-7.8880497490596895
				]
			]
		},
		{
			"type": "text",
			"version": 592,
			"versionNonce": 911163778,
			"isDeleted": false,
			"id": "V1lGIYxe",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -439.5160266513913,
			"y": -180.4225088431574,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 912.4121704101562,
			"height": 48,
			"seed": 1353523709,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029724,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 3,
			"text": "process -> OS가 자원을 관리하는 단위.\nprogram -> Routine, Procedure 이라고 불리는 명령어의 집합을 처리 일련의 연산을 수행하는 주체",
			"rawText": "process -> OS가 자원을 관리하는 단위.\nprogram -> Routine, Procedure 이라고 불리는 명령어의 집합을 처리 일련의 연산을 수행하는 주체",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "process -> OS가 자원을 관리하는 단위.\nprogram -> Routine, Procedure 이라고 불리는 명령어의 집합을 처리 일련의 연산을 수행하는 주체",
			"lineHeight": 1.2,
			"baseline": 44
		},
		{
			"type": "rectangle",
			"version": 246,
			"versionNonce": 174133150,
			"isDeleted": false,
			"id": "r9-apJ6pSfSZ4sbniHqSk",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -385.5139572559369,
			"y": 50.048229299994546,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 854.4692262229381,
			"height": 1.2251502303088742,
			"seed": 1026460467,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [],
			"updated": 1700563029724,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 376,
			"versionNonce": 330285378,
			"isDeleted": false,
			"id": "XKqTg-ITjIhnM3JZw-_hp",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -385.5139572559369,
			"y": 177.09947540835117,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 854.4692262229381,
			"height": 1.2251502303088742,
			"seed": 1215606045,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [],
			"updated": 1700563029724,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 118,
			"versionNonce": 286878686,
			"isDeleted": false,
			"id": "UaRCjDDA",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -385.5139572559369,
			"y": 25.29119402739036,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 70.3125,
			"height": 48,
			"seed": 84128637,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029724,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 3,
			"text": "User\nKernel",
			"rawText": "User\nKernel",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "User\nKernel",
			"lineHeight": 1.2,
			"baseline": 44
		},
		{
			"type": "text",
			"version": 185,
			"versionNonce": 946489602,
			"isDeleted": false,
			"id": "bnkPpsZI",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -385.5139572559369,
			"y": 151.78170700435032,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 35.15625,
			"height": 48,
			"seed": 924159635,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029724,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 3,
			"text": "S/W\nH/W",
			"rawText": "S/W\nH/W",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "S/W\nH/W",
			"lineHeight": 1.2,
			"baseline": 44
		},
		{
			"type": "rectangle",
			"version": 241,
			"versionNonce": 447189005,
			"isDeleted": false,
			"id": "12Vjh97BW8Cpp0ZPL9HL2",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 905.0347879863627,
			"y": -659.5618960127529,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 510.8016304347825,
			"height": 517.1942934782608,
			"seed": 277272659,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [],
			"updated": 1700975484024,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 125,
			"versionNonce": 573924963,
			"isDeleted": false,
			"id": "Y0h2gp4ZzD4noYB5za7x2",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 961.4487734388315,
			"y": -540.079934942888,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 400.84578804347825,
			"height": 234.25951086956525,
			"seed": 174550835,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [],
			"updated": 1700975529353,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 133,
			"versionNonce": 1845136478,
			"isDeleted": false,
			"id": "aLL2aY4xfxfWlA6PPcBli",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 982.069924601617,
			"y": -503.0116567491094,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 351.57608695652175,
			"height": 103.02989130434781,
			"seed": 678252797,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [],
			"updated": 1700563029724,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 116,
			"versionNonce": 1966209987,
			"isDeleted": false,
			"id": "OAXC0a93v8EQKDOWfeom-",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1009.2071528624865,
			"y": -481.1155969665007,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 69,
			"height": 59,
			"seed": 745605011,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"type": "text",
					"id": "ASzwZ4Wf"
				}
			],
			"updated": 1700975477671,
			"link": null,
			"locked": false
		},
		{
			"id": "ASzwZ4Wf",
			"type": "text",
			"x": 1020.2696528624865,
			"y": -461.2155969665007,
			"width": 46.875,
			"height": 19.2,
			"angle": 0,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#eebefa",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"seed": 1164876291,
			"version": 10,
			"versionNonce": 1054799907,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1700975476456,
			"link": null,
			"locked": false,
			"text": "MySQL",
			"rawText": "MySQL",
			"fontSize": 16,
			"fontFamily": 3,
			"textAlign": "center",
			"verticalAlign": "middle",
			"baseline": 15,
			"containerId": "OAXC0a93v8EQKDOWfeom-",
			"originalText": "MySQL",
			"lineHeight": 1.2
		},
		{
			"type": "rectangle",
			"version": 186,
			"versionNonce": 1436977955,
			"isDeleted": false,
			"id": "mx1ee3fOvyafcGsVTOGtv",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1111.3702184421095,
			"y": -486.6272480380441,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 96,
			"height": 68,
			"seed": 233056637,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"type": "text",
					"id": "W1RJ3MCf"
				}
			],
			"updated": 1700975471133,
			"link": null,
			"locked": false
		},
		{
			"id": "W1RJ3MCf",
			"type": "text",
			"x": 1117.1827184421095,
			"y": -471.8272480380441,
			"width": 84.375,
			"height": 38.4,
			"angle": 0,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#eebefa",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"seed": 463535373,
			"version": 109,
			"versionNonce": 641035405,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1700975471133,
			"link": null,
			"locked": false,
			"text": "WordPress\n+ PHP",
			"rawText": "WordPress\n+ PHP",
			"fontSize": 16,
			"fontFamily": 3,
			"textAlign": "center",
			"verticalAlign": "middle",
			"baseline": 34,
			"containerId": "mx1ee3fOvyafcGsVTOGtv",
			"originalText": "WordPress\n+ PHP",
			"lineHeight": 1.2
		},
		{
			"type": "rectangle",
			"version": 163,
			"versionNonce": 1978426051,
			"isDeleted": false,
			"id": "DwUS57Wxg3WfD0socruzy",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1236.943660454794,
			"y": -482.9870599167867,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 69,
			"height": 59,
			"seed": 831960531,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"type": "text",
					"id": "EQxOzjek"
				}
			],
			"updated": 1700975481356,
			"link": null,
			"locked": false
		},
		{
			"id": "EQxOzjek",
			"type": "text",
			"x": 1248.006160454794,
			"y": -463.0870599167867,
			"width": 46.875,
			"height": 19.2,
			"angle": 0,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#eebefa",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"seed": 773806381,
			"version": 26,
			"versionNonce": 2006081261,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1700975481356,
			"link": null,
			"locked": false,
			"text": "NGINX",
			"rawText": "NGINX",
			"fontSize": 16,
			"fontFamily": 3,
			"textAlign": "center",
			"verticalAlign": "middle",
			"baseline": 15,
			"containerId": "DwUS57Wxg3WfD0socruzy",
			"originalText": "NGINX",
			"lineHeight": 1.2
		},
		{
			"type": "rectangle",
			"version": 151,
			"versionNonce": 1416465630,
			"isDeleted": false,
			"id": "Vn2kfcXTSzACeLiXoxfFS",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1008.4388104711823,
			"y": -376.133260009979,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 69.3716032608695,
			"height": 54.40557065217388,
			"seed": 705951891,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [],
			"updated": 1700563029724,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 186,
			"versionNonce": 480557058,
			"isDeleted": false,
			"id": "nlGIaRAjZ2Rh2TOaqQ9RN",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1123.036296884225,
			"y": -375.5609094665007,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 69.3716032608695,
			"height": 54.40557065217388,
			"seed": 80419357,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [],
			"updated": 1700563029724,
			"link": null,
			"locked": false
		},
		{
			"type": "line",
			"version": 120,
			"versionNonce": 744464653,
			"isDeleted": false,
			"id": "qZH1m0oXYKKjnonrIqpqU",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1042.5420713407475,
			"y": -420.82755348823986,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 0.08777771874156315,
			"height": 44.718070652173935,
			"seed": 296388723,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1700975479106,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-0.08777771874156315,
					44.718070652173935
				]
			]
		},
		{
			"type": "line",
			"version": 107,
			"versionNonce": 756180930,
			"isDeleted": false,
			"id": "i65MSeRW-ntRomqLTLrgB",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1158.0719626450953,
			"y": -418.29018935780505,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 0.04076086956524705,
			"height": 43.11141304347825,
			"seed": 521454237,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1700563029724,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0.04076086956524705,
					43.11141304347825
				]
			]
		},
		{
			"type": "rectangle",
			"version": 253,
			"versionNonce": 180103501,
			"isDeleted": false,
			"id": "_NlYq8LSFMZMaVXnGvzrr",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "dashed",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 987.9953816174275,
			"y": -390.09543551214705,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 231.3722826086955,
			"height": 78.11757701081699,
			"seed": 426118099,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [],
			"updated": 1700975504498,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 203,
			"versionNonce": 196353922,
			"isDeleted": false,
			"id": "gdYgehmg",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "dashed",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -304.45921596815805,
			"y": 213.28770524302098,
			"strokeColor": "#1971c2",
			"backgroundColor": "transparent",
			"width": 46.875,
			"height": 48,
			"seed": 370981885,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029724,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 3,
			"text": "CPU\ncore",
			"rawText": "CPU\ncore",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "CPU\ncore",
			"lineHeight": 1.2,
			"baseline": 44
		},
		{
			"type": "rectangle",
			"version": 333,
			"versionNonce": 1354830238,
			"isDeleted": false,
			"id": "J9M0hRr3RNhKId0p0fb1G",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -249.89127511994377,
			"y": 218.78770524302098,
			"strokeColor": "#1971c2",
			"backgroundColor": "transparent",
			"width": 36,
			"height": 37,
			"seed": 813683741,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"type": "text",
					"id": "08Vb3B2n"
				}
			],
			"updated": 1700563029724,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 165,
			"versionNonce": 1690885954,
			"isDeleted": false,
			"id": "08Vb3B2n",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -237.75065011994377,
			"y": 225.28770524302098,
			"strokeColor": "#1971c2",
			"backgroundColor": "transparent",
			"width": 11.71875,
			"height": 24,
			"seed": 201956541,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029724,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 3,
			"text": "0",
			"rawText": "0",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "J9M0hRr3RNhKId0p0fb1G",
			"originalText": "0",
			"lineHeight": 1.2,
			"baseline": 20
		},
		{
			"type": "rectangle",
			"version": 386,
			"versionNonce": 1344875998,
			"isDeleted": false,
			"id": "-0rxrcCpK_U-E5K7osswl",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -206.19833427172952,
			"y": 218.78770524302098,
			"strokeColor": "#1971c2",
			"backgroundColor": "#2f9e44",
			"width": 36,
			"height": 37,
			"seed": 969565469,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"type": "text",
					"id": "PDhFkfr0"
				}
			],
			"updated": 1700563029724,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 165,
			"versionNonce": 78620418,
			"isDeleted": false,
			"id": "PDhFkfr0",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -194.05770927172952,
			"y": 225.28770524302098,
			"strokeColor": "#1971c2",
			"backgroundColor": "transparent",
			"width": 11.71875,
			"height": 24,
			"seed": 952113629,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029724,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 3,
			"text": "1",
			"rawText": "1",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "-0rxrcCpK_U-E5K7osswl",
			"originalText": "1",
			"lineHeight": 1.2,
			"baseline": 20
		},
		{
			"type": "rectangle",
			"version": 350,
			"versionNonce": 482591262,
			"isDeleted": false,
			"id": "9tONa2sJ7LhAS7oYpE8WP",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -162.50539342351527,
			"y": 218.78770524302098,
			"strokeColor": "#1971c2",
			"backgroundColor": "#a5d8ff",
			"width": 36,
			"height": 37,
			"seed": 2065283741,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"type": "text",
					"id": "HTwjdNag"
				}
			],
			"updated": 1700563029724,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 165,
			"versionNonce": 1407678146,
			"isDeleted": false,
			"id": "HTwjdNag",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -150.36476842351527,
			"y": 225.28770524302098,
			"strokeColor": "#1971c2",
			"backgroundColor": "transparent",
			"width": 11.71875,
			"height": 24,
			"seed": 232663805,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029725,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 3,
			"text": "2",
			"rawText": "2",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "9tONa2sJ7LhAS7oYpE8WP",
			"originalText": "2",
			"lineHeight": 1.2,
			"baseline": 20
		},
		{
			"type": "rectangle",
			"version": 397,
			"versionNonce": 1501679198,
			"isDeleted": false,
			"id": "85PL3tR50e7lx106Cj6zC",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -118.81245257530102,
			"y": 218.78770524302098,
			"strokeColor": "#1971c2",
			"backgroundColor": "transparent",
			"width": 36,
			"height": 37,
			"seed": 1352818429,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"type": "text",
					"id": "0t0gcBlf"
				}
			],
			"updated": 1700563029725,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 164,
			"versionNonce": 1393512066,
			"isDeleted": false,
			"id": "0t0gcBlf",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -106.67182757530102,
			"y": 225.28770524302098,
			"strokeColor": "#1971c2",
			"backgroundColor": "transparent",
			"width": 11.71875,
			"height": 24,
			"seed": 370954269,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029725,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 3,
			"text": "3",
			"rawText": "3",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "85PL3tR50e7lx106Cj6zC",
			"originalText": "3",
			"lineHeight": 1.2,
			"baseline": 20
		},
		{
			"type": "text",
			"version": 735,
			"versionNonce": 590631582,
			"isDeleted": false,
			"id": "l2NnNpvf",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -387.2753812125927,
			"y": 90.60430193549672,
			"strokeColor": "#1971c244",
			"backgroundColor": "transparent",
			"width": 47.472625732421875,
			"height": 48.6133333333333,
			"seed": 574043699,
			"groupIds": [
				"zD4-fkpvirXltOlJlaCh9"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029725,
			"link": null,
			"locked": false,
			"fontSize": 40.511111111111084,
			"fontFamily": 3,
			"text": "OS",
			"rawText": "OS",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "OS",
			"lineHeight": 1.2,
			"baseline": 39
		},
		{
			"type": "text",
			"version": 801,
			"versionNonce": 384183874,
			"isDeleted": false,
			"id": "xNH4aHl0",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -326.63550026021164,
			"y": 102.91096860216336,
			"strokeColor": "#1971c2bb",
			"backgroundColor": "transparent",
			"width": 151.231201171875,
			"height": 24,
			"seed": 1984664445,
			"groupIds": [
				"zD4-fkpvirXltOlJlaCh9"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029725,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 3,
			"text": "자원 관리 + I/O",
			"rawText": "자원 관리 + I/O",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "자원 관리 + I/O",
			"lineHeight": 1.2,
			"baseline": 20
		},
		{
			"type": "rectangle",
			"version": 152,
			"versionNonce": 1418481374,
			"isDeleted": false,
			"id": "w0l63GhlQ-CRymF5R5Jtk",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -284.417921325301,
			"y": -39.065903387931385,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 106,
			"height": 71,
			"seed": 1865297981,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"type": "text",
					"id": "r52SRCPH"
				}
			],
			"updated": 1700563029725,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 113,
			"versionNonce": 1145771522,
			"isDeleted": false,
			"id": "r52SRCPH",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -254.855421325301,
			"y": -27.565903387931385,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 46.875,
			"height": 48,
			"seed": 277114013,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029725,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 3,
			"text": "PID\n1000",
			"rawText": "PID\n1000",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "w0l63GhlQ-CRymF5R5Jtk",
			"originalText": "PID\n1000",
			"lineHeight": 1.2,
			"baseline": 44
		},
		{
			"type": "rectangle",
			"version": 179,
			"versionNonce": 1243267870,
			"isDeleted": false,
			"id": "YYLCYmnAPNp9nr6k6zS0O",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -134.94433501577737,
			"y": -39.065903387931385,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 106,
			"height": 71,
			"seed": 1313411741,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"type": "text",
					"id": "x9rLlIky"
				}
			],
			"updated": 1700563029725,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 152,
			"versionNonce": 205325762,
			"isDeleted": false,
			"id": "x9rLlIky",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -105.38183501577737,
			"y": -27.565903387931385,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 46.875,
			"height": 48,
			"seed": 874952445,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029725,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 3,
			"text": "PID\n1001",
			"rawText": "PID\n1001",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "YYLCYmnAPNp9nr6k6zS0O",
			"originalText": "PID\n1001",
			"lineHeight": 1.2,
			"baseline": 44
		},
		{
			"type": "text",
			"version": 100,
			"versionNonce": 642821982,
			"isDeleted": false,
			"id": "Bc0Wm0Oe",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -57.82231120625352,
			"y": 225.28770524302098,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 23.4375,
			"height": 24,
			"seed": 525032051,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029725,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 3,
			"text": "+ ",
			"rawText": "+ ",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "+ ",
			"lineHeight": 1.2,
			"baseline": 20
		},
		{
			"type": "rectangle",
			"version": 271,
			"versionNonce": 668663170,
			"isDeleted": false,
			"id": "_1-kC219p_GuiN9G5zkFi",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1.723819746127333,
			"y": 227.80630643349713,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 324.270833333333,
			"height": 21.000744047619254,
			"seed": 1904882813,
			"groupIds": [
				"Bgj79ZDBx4ltdDqxyRoSo"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029725,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 187,
			"versionNonce": 360649630,
			"isDeleted": false,
			"id": "asl1Ifvf",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 4.654623317555831,
			"y": 225.28770524302098,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 316.40625,
			"height": 24,
			"seed": 1732373597,
			"groupIds": [
				"Bgj79ZDBx4ltdDqxyRoSo"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029725,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 3,
			"text": "|||||||||||||||||||||||||||",
			"rawText": "|||||||||||||||||||||||||||",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "|||||||||||||||||||||||||||",
			"lineHeight": 1.2,
			"baseline": 20
		},
		{
			"type": "text",
			"version": 95,
			"versionNonce": 1415839042,
			"isDeleted": false,
			"id": "gxyGPwlQ",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 0.5593852223177009,
			"y": 201.5987171477828,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 35.15625,
			"height": 24,
			"seed": 1828505853,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029725,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 3,
			"text": "RAM",
			"rawText": "RAM",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "RAM",
			"lineHeight": 1.2,
			"baseline": 20
		},
		{
			"type": "line",
			"version": 315,
			"versionNonce": 299298782,
			"isDeleted": false,
			"id": "7QPl1QJZgGrm5F3b62lhK",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -221.27841239672966,
			"y": 33.075651671592425,
			"strokeColor": "#2f9e44bb",
			"backgroundColor": "transparent",
			"width": 34.76562499999994,
			"height": 184.7656249999999,
			"seed": 1918348029,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029725,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					17.29166666666663,
					98.1994047619047
				],
				[
					34.76562499999994,
					184.7656249999999
				]
			]
		},
		{
			"type": "line",
			"version": 709,
			"versionNonce": 1329005826,
			"isDeleted": false,
			"id": "Mz8Qc--XAGdgNboftHZX5",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -220.34091239672966,
			"y": 31.65824095730676,
			"strokeColor": "#2f9e44bb",
			"backgroundColor": "transparent",
			"width": 292.80877976190465,
			"height": 195.111607142857,
			"seed": 1421372061,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029725,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					210.52827380952363,
					113.71279761904748
				],
				[
					292.80877976190465,
					195.111607142857
				]
			]
		},
		{
			"type": "rectangle",
			"version": 474,
			"versionNonce": 661210142,
			"isDeleted": false,
			"id": "2CkPFUGyE-JgUhb7e6abn",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 68.922480460413,
			"y": 228.01984810016376,
			"strokeColor": "#2f9e4444",
			"backgroundColor": "#2f9e4444",
			"width": 34.91548736289617,
			"height": 19.025297619047706,
			"seed": 1302768733,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "vWP33N5TnX94JD4B9Gx7F",
					"type": "arrow"
				}
			],
			"updated": 1700563029725,
			"link": null,
			"locked": false
		},
		{
			"type": "line",
			"version": 386,
			"versionNonce": 1372787906,
			"isDeleted": false,
			"id": "lOA0BEzrytnh1J-A41exU",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -10.59016834911074,
			"y": 146.30481833825888,
			"strokeColor": "#2f9e4444",
			"backgroundColor": "#2f9e4444",
			"width": 249.58333333333314,
			"height": 80.52083333333326,
			"seed": 284540915,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029725,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					201.80040620355862,
					20.01226851682418
				],
				[
					249.58333333333314,
					80.52083333333326
				]
			]
		},
		{
			"type": "rectangle",
			"version": 249,
			"versionNonce": 942084190,
			"isDeleted": false,
			"id": "y06jFg1SVTACBLAzKMARt",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 233.7859477223177,
			"y": 228.7036278620684,
			"strokeColor": "#2f9e4444",
			"backgroundColor": "#2f9e4444",
			"width": 34.36383928571422,
			"height": 19.025297619047706,
			"seed": 1177774941,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029725,
			"link": null,
			"locked": false
		},
		{
			"type": "line",
			"version": 152,
			"versionNonce": 232205442,
			"isDeleted": false,
			"id": "Y2opJ9tLyXK6n9aQibZvZ",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -79.80891834911063,
			"y": 32.39856833825888,
			"strokeColor": "#1971c2bb",
			"backgroundColor": "#2f9e44",
			"width": 64.79538690476187,
			"height": 186.68898809523796,
			"seed": 2099064445,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029725,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-64.79538690476187,
					186.68898809523796
				]
			]
		},
		{
			"type": "line",
			"version": 434,
			"versionNonce": 1071731870,
			"isDeleted": false,
			"id": "6uVyz_HUvSVqROdcb-6AS",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -80.47112073006298,
			"y": 32.294401671592254,
			"strokeColor": "#1971c2bb",
			"backgroundColor": "#2f9e44",
			"width": 227.42529577218846,
			"height": 195.01723864227694,
			"seed": 369083933,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029725,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					227.42529577218846,
					195.01723864227694
				]
			]
		},
		{
			"type": "rectangle",
			"version": 311,
			"versionNonce": 688016450,
			"isDeleted": false,
			"id": "NG22MGh96o67txyy4FS5K",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 140.22270367469883,
			"y": 228.4699969096871,
			"strokeColor": "#1971c244",
			"backgroundColor": "#a5d8ff44",
			"width": 34.36383928571422,
			"height": 19.025297619047706,
			"seed": 1836490301,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "vWP33N5TnX94JD4B9Gx7F",
					"type": "arrow"
				}
			],
			"updated": 1700563029725,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 682,
			"versionNonce": 407441630,
			"isDeleted": false,
			"id": "Le16jlY0",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -0.08585924221159758,
			"y": 298.83761492912055,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#a5d8ff",
			"width": 317.00537109375,
			"height": 82.1392007584562,
			"seed": 1343474557,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029725,
			"link": null,
			"locked": false,
			"fontSize": 17.11233349134504,
			"fontFamily": 3,
			"text": "PID 1000이 할당받은 영역을 벗어난다면 \nPID 1001에 데이터가 씌워질 수 있음.\nOS가 이런 일이 일어나지 않도록 막아준다.\n",
			"rawText": "PID 1000이 할당받은 영역을 벗어난다면 \nPID 1001에 데이터가 씌워질 수 있음.\nOS가 이런 일이 일어나지 않도록 막아준다.\n",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "PID 1000이 할당받은 영역을 벗어난다면 \nPID 1001에 데이터가 씌워질 수 있음.\nOS가 이런 일이 일어나지 않도록 막아준다.\n",
			"lineHeight": 1.2,
			"baseline": 78
		},
		{
			"type": "arrow",
			"version": 506,
			"versionNonce": 959673346,
			"isDeleted": false,
			"id": "vWP33N5TnX94JD4B9Gx7F",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 92.38008245248649,
			"y": 256.66105465022343,
			"strokeColor": "#1971c2",
			"backgroundColor": "#a5d8ff",
			"width": 67.54709575740223,
			"height": 29.81053120750255,
			"seed": 545417331,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1700563029725,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "2CkPFUGyE-JgUhb7e6abn",
				"gap": 9.615908931011973,
				"focus": 0.5224652399103279
			},
			"endBinding": {
				"elementId": "NG22MGh96o67txyy4FS5K",
				"focus": -0.8253299405988084,
				"gap": 7.643100700429329
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					30.196296673430695,
					28.287871786443247
				],
				[
					67.54709575740223,
					-1.522659421059302
				]
			]
		},
		{
			"type": "rectangle",
			"version": 279,
			"versionNonce": 1022313758,
			"isDeleted": false,
			"id": "2B3ZtkZ07UBLmqY-XM21p",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 126.31951716421591,
			"y": -35.57247812647722,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 106,
			"height": 71,
			"seed": 267613843,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"type": "text",
					"id": "0KVOjj9O"
				}
			],
			"updated": 1700563029725,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 256,
			"versionNonce": 1080665026,
			"isDeleted": false,
			"id": "0KVOjj9O",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 155.8820171642159,
			"y": -24.072478126477222,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 46.875,
			"height": 48,
			"seed": 772615219,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029725,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 3,
			"text": "PID\n2000",
			"rawText": "PID\n2000",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "2B3ZtkZ07UBLmqY-XM21p",
			"originalText": "PID\n2000",
			"lineHeight": 1.2,
			"baseline": 44
		},
		{
			"type": "rectangle",
			"version": 307,
			"versionNonce": 256176478,
			"isDeleted": false,
			"id": "p1UVih9Jd2hdWvxUTGzsq",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 70.3967669595325,
			"y": -52.55821755061754,
			"strokeColor": "#e03131",
			"backgroundColor": "transparent",
			"width": 217.84550040936682,
			"height": 189.91057908773666,
			"seed": 1131161779,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029725,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 183,
			"versionNonce": 683924354,
			"isDeleted": false,
			"id": "hY0O2Jie",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 185.77351736889932,
			"y": -87.32940548696172,
			"strokeColor": "#e03131",
			"backgroundColor": "transparent",
			"width": 128.90625,
			"height": 24,
			"seed": 215021917,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029725,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 3,
			"text": "container: ",
			"rawText": "container: ",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "container: ",
			"lineHeight": 1.2,
			"baseline": 20
		},
		{
			"type": "text",
			"version": 338,
			"versionNonce": 446371230,
			"isDeleted": false,
			"id": "vO1aHkXk",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 308.4443423592186,
			"y": -87.32940548696172,
			"strokeColor": "#e03131",
			"backgroundColor": "transparent",
			"width": 336.506103515625,
			"height": 96,
			"seed": 867991677,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029725,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 3,
			"text": "커널과 H/W는 공유\nHost OS 입장에서 보면 \nDocker 또한 프로세스로 관리가 된다.\n",
			"rawText": "커널과 H/W는 공유\nHost OS 입장에서 보면 \nDocker 또한 프로세스로 관리가 된다.\n",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "커널과 H/W는 공유\nHost OS 입장에서 보면 \nDocker 또한 프로세스로 관리가 된다.\n",
			"lineHeight": 1.2,
			"baseline": 92
		},
		{
			"type": "text",
			"version": 222,
			"versionNonce": 1082202946,
			"isDeleted": false,
			"id": "b2tUclJH",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -392.01379079958974,
			"y": 514.4740335386533,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 170.33578491210938,
			"height": 78.77581521739127,
			"seed": 328952627,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029725,
			"link": null,
			"locked": false,
			"fontSize": 65.6465126811594,
			"fontFamily": 3,
			"text": "가상화",
			"rawText": "가상화",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "가상화",
			"lineHeight": 1.2,
			"baseline": 63
		},
		{
			"type": "rectangle",
			"version": 299,
			"versionNonce": 1478668766,
			"isDeleted": false,
			"id": "XCDPvSTrtm70bTmSRzWeT",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -377.6802161769564,
			"y": 762.0475919428717,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 854.4692262229381,
			"height": 1.2251502303088742,
			"seed": 894591731,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [],
			"updated": 1700563029725,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 429,
			"versionNonce": 905995010,
			"isDeleted": false,
			"id": "NYa1WFpcdhb8Zo2F9L76p",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -377.6802161769564,
			"y": 889.0988380512283,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 854.4692262229381,
			"height": 1.2251502303088742,
			"seed": 898600083,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [],
			"updated": 1700563029725,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 171,
			"versionNonce": 1928119838,
			"isDeleted": false,
			"id": "ETjP3eDJ",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -377.6802161769564,
			"y": 737.2905566702675,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 70.3125,
			"height": 48,
			"seed": 867598899,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029725,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 3,
			"text": "User\nKernel",
			"rawText": "User\nKernel",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "User\nKernel",
			"lineHeight": 1.2,
			"baseline": 44
		},
		{
			"type": "text",
			"version": 238,
			"versionNonce": 331395778,
			"isDeleted": false,
			"id": "jZYuSgpv",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -377.6802161769564,
			"y": 863.7810696472275,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 35.15625,
			"height": 48,
			"seed": 1756218323,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029725,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 3,
			"text": "S/W\nH/W",
			"rawText": "S/W\nH/W",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "S/W\nH/W",
			"lineHeight": 1.2,
			"baseline": 44
		},
		{
			"type": "rectangle",
			"version": 142,
			"versionNonce": 199905886,
			"isDeleted": false,
			"id": "9GAu-i9eZhtEHitaO1tL-",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -213.72024293208867,
			"y": 629.7217761779424,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 139,
			"height": 73,
			"seed": 615520339,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"type": "text",
					"id": "vOHbpFom"
				}
			],
			"updated": 1700563029725,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 121,
			"versionNonce": 1012992642,
			"isDeleted": false,
			"id": "vOHbpFom",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -185.23586793208867,
			"y": 654.2217761779424,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 82.03125,
			"height": 24,
			"seed": 150163837,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029725,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 3,
			"text": "process",
			"rawText": "process",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "9GAu-i9eZhtEHitaO1tL-",
			"originalText": "process",
			"lineHeight": 1.2,
			"baseline": 20
		},
		{
			"type": "ellipse",
			"version": 977,
			"versionNonce": 2112640670,
			"isDeleted": false,
			"id": "6s8JPQetQMCTnQk-jfwQf",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -168.27210359628594,
			"y": 707.8083762404955,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 48.10372132839456,
			"height": 48.10372132839456,
			"seed": 381341181,
			"groupIds": [
				"2OIwqXuHoscQnRhTAA5eo"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029725,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 124,
			"versionNonce": 1721788994,
			"isDeleted": false,
			"id": "TCOwTU8k",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -167.65774293208867,
			"y": 719.8602369046928,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 46.875,
			"height": 24,
			"seed": 1563442013,
			"groupIds": [
				"2OIwqXuHoscQnRhTAA5eo"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029725,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 3,
			"text": "file",
			"rawText": "file",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "file",
			"lineHeight": 1.2,
			"baseline": 20
		},
		{
			"type": "rectangle",
			"version": 191,
			"versionNonce": 564384478,
			"isDeleted": false,
			"id": "xumBHWBaD-EJWInrI694C",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -213.72024293208867,
			"y": 763.1004942544661,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 139,
			"height": 73,
			"seed": 1123862291,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"type": "text",
					"id": "0qoLnarC"
				}
			],
			"updated": 1700563029725,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 181,
			"versionNonce": 425579010,
			"isDeleted": false,
			"id": "0qoLnarC",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -178.82021851802617,
			"y": 787.6004942544661,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 69.199951171875,
			"height": 24,
			"seed": 1150839987,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029725,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 3,
			"text": "구성요소",
			"rawText": "구성요소",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "xumBHWBaD-EJWInrI694C",
			"originalText": "구성요소",
			"lineHeight": 1.2,
			"baseline": 20
		},
		{
			"type": "rectangle",
			"version": 232,
			"versionNonce": 295814942,
			"isDeleted": false,
			"id": "a-qYPJkbi7tuxqSbdgrc_",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -213.72024293208867,
			"y": 855.6300180079853,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 139,
			"height": 34,
			"seed": 539609587,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"type": "text",
					"id": "6E1v3UXM"
				}
			],
			"updated": 1700563029725,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 228,
			"versionNonce": 664289730,
			"isDeleted": false,
			"id": "6E1v3UXM",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -179.37649293208867,
			"y": 860.6300180079853,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 70.3125,
			"height": 24,
			"seed": 1055003539,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029725,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 3,
			"text": "driver",
			"rawText": "driver",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "a-qYPJkbi7tuxqSbdgrc_",
			"originalText": "driver",
			"lineHeight": 1.2,
			"baseline": 20
		},
		{
			"type": "text",
			"version": 134,
			"versionNonce": 1851208542,
			"isDeleted": false,
			"id": "5YOlD0Yt",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -232.16637446534025,
			"y": 944.8602043673174,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 35.15625,
			"height": 24,
			"seed": 1534857085,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029725,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 3,
			"text": "CPU",
			"rawText": "CPU",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "CPU",
			"lineHeight": 1.2,
			"baseline": 20
		},
		{
			"type": "rectangle",
			"version": 341,
			"versionNonce": 745453954,
			"isDeleted": false,
			"id": "5Gu15Zv1GOIQCkWhhy3gO",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -168.54453813775848,
			"y": 923.111804799646,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 91.24274168313781,
			"height": 67.49679913534271,
			"seed": 1609523123,
			"groupIds": [
				"scof1zWEJiAtzHdXZ240O"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029725,
			"link": null,
			"locked": false
		},
		{
			"type": "line",
			"version": 230,
			"versionNonce": 571807646,
			"isDeleted": false,
			"id": "dpXiq4qEopzm5ohDe3BJH",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -168.25536180882108,
			"y": 956.7658415652431,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 90.664389025263,
			"height": 0.18872560414854433,
			"seed": 297156285,
			"groupIds": [
				"scof1zWEJiAtzHdXZ240O"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029725,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					90.664389025263,
					0.18872560414854433
				]
			]
		},
		{
			"type": "line",
			"version": 206,
			"versionNonce": 119552322,
			"isDeleted": false,
			"id": "qPuqTXU4rXZr-KqjdkvYf",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -123.21386560580558,
			"y": 923.1361564905039,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 0.5813966192320095,
			"height": 66.46794019659706,
			"seed": 822827123,
			"groupIds": [
				"scof1zWEJiAtzHdXZ240O"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029725,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0.5813966192320095,
					66.46794019659706
				]
			]
		},
		{
			"type": "text",
			"version": 123,
			"versionNonce": 621573086,
			"isDeleted": false,
			"id": "8CMjTxXe",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -43.62340799816579,
			"y": 944.8602043673174,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 11.71875,
			"height": 24,
			"seed": 133131773,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029725,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 3,
			"text": "+",
			"rawText": "+",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "+",
			"lineHeight": 1.2,
			"baseline": 20
		},
		{
			"type": "rectangle",
			"version": 174,
			"versionNonce": 1460388098,
			"isDeleted": false,
			"id": "UJjNHx6itjIt3K3xJ_SdO",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1.9801291134406256,
			"y": 922.8602043673174,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 115,
			"height": 68,
			"seed": 1191131635,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"type": "text",
					"id": "njr7x9dv"
				}
			],
			"updated": 1700563029725,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 125,
			"versionNonce": 1095649310,
			"isDeleted": false,
			"id": "njr7x9dv",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 41.902004113440626,
			"y": 944.8602043673174,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 35.15625,
			"height": 24,
			"seed": 681435261,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029725,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 3,
			"text": "RAM",
			"rawText": "RAM",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "UJjNHx6itjIt3K3xJ_SdO",
			"originalText": "RAM",
			"lineHeight": 1.2,
			"baseline": 20
		},
		{
			"type": "text",
			"version": 123,
			"versionNonce": 2008043714,
			"isDeleted": false,
			"id": "sFj4mngX",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 163.6581845841512,
			"y": 944.8602043673174,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 11.71875,
			"height": 24,
			"seed": 59830877,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029725,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 3,
			"text": "+",
			"rawText": "+",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "+",
			"lineHeight": 1.2,
			"baseline": 20
		},
		{
			"type": "rectangle",
			"version": 203,
			"versionNonce": 1456182366,
			"isDeleted": false,
			"id": "Qwu-sHyr-2ioY1QDal9Yz",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 199.8787108120788,
			"y": 922.8602043673174,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 115,
			"height": 68,
			"seed": 1233638269,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"type": "text",
					"id": "8mGnH6Yo"
				}
			],
			"updated": 1700563029725,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 156,
			"versionNonce": 2091706498,
			"isDeleted": false,
			"id": "8mGnH6Yo",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 239.8005858120788,
			"y": 944.8602043673174,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 35.15625,
			"height": 24,
			"seed": 1603951581,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029725,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 3,
			"text": "HDD",
			"rawText": "HDD",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "Qwu-sHyr-2ioY1QDal9Yz",
			"originalText": "HDD",
			"lineHeight": 1.2,
			"baseline": 20
		},
		{
			"type": "text",
			"version": 153,
			"versionNonce": 525686942,
			"isDeleted": false,
			"id": "8osMrjTV",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -163.89945310661696,
			"y": 930.5867760924991,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 36.2578125,
			"height": 18.574832903916978,
			"seed": 271696947,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029726,
			"link": null,
			"locked": false,
			"fontSize": 15.479027419930816,
			"fontFamily": 3,
			"text": "core",
			"rawText": "core",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "core",
			"lineHeight": 1.2,
			"baseline": 15
		},
		{
			"type": "text",
			"version": 267,
			"versionNonce": 767592514,
			"isDeleted": false,
			"id": "qDExiQuE",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -56.755057293280174,
			"y": 626.0080026875028,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 347.1123046875,
			"height": 24,
			"seed": 1041890653,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029726,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 3,
			"text": "자신만의 고유한 메모리를 보장 받는다. ",
			"rawText": "자신만의 고유한 메모리를 보장 받는다. ",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "자신만의 고유한 메모리를 보장 받는다. ",
			"lineHeight": 1.2,
			"baseline": 20
		},
		{
			"type": "text",
			"version": 138,
			"versionNonce": 1922864350,
			"isDeleted": false,
			"id": "O87Gj7sH",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -52.94401767402127,
			"y": 652.1891143210862,
			"strokeColor": "#e03131",
			"backgroundColor": "transparent",
			"width": 290.1873779296875,
			"height": 48,
			"seed": 79579165,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029726,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 3,
			"text": "== virtual memory\nprocess마다 독립적인 공간이다.",
			"rawText": "== virtual memory\nprocess마다 독립적인 공간이다.",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "== virtual memory\nprocess마다 독립적인 공간이다.",
			"lineHeight": 1.2,
			"baseline": 44
		},
		{
			"type": "rectangle",
			"version": 182,
			"versionNonce": 46804994,
			"isDeleted": false,
			"id": "IbVEHjKBwxx6qbDp7loyz",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 314.3191298338206,
			"y": 607.0546244605471,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 127,
			"height": 83,
			"seed": 529754899,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"type": "text",
					"id": "tq0J1WQH"
				}
			],
			"updated": 1700563029726,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 137,
			"versionNonce": 171067678,
			"isDeleted": false,
			"id": "tq0J1WQH",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 336.8035048338206,
			"y": 624.5546244605471,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 82.03125,
			"height": 48,
			"seed": 1816561011,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029726,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 3,
			"text": "MS-Word\n#1",
			"rawText": "MS-Word\n#1",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "IbVEHjKBwxx6qbDp7loyz",
			"originalText": "MS-Word\n#1",
			"lineHeight": 1.2,
			"baseline": 44
		},
		{
			"type": "line",
			"version": 222,
			"versionNonce": 533258178,
			"isDeleted": false,
			"id": "6_84SPOMECi4UZy2bFvS0",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -12.224946598280326,
			"y": 932.4770760953425,
			"strokeColor": "#1971c2",
			"backgroundColor": "transparent",
			"width": 339.34385606598454,
			"height": 26.299826126515768,
			"seed": 798238547,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029726,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-0.082186956645387,
					-26.299826126515768
				],
				[
					339.26166910933915,
					-25.237483612840606
				],
				[
					339.1003391574057,
					-0.36527536286826034
				]
			]
		},
		{
			"type": "line",
			"version": 111,
			"versionNonce": 1166505310,
			"isDeleted": false,
			"id": "iwZxkrjOzXe4xuNHxr20v",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 154.84591645495402,
			"y": 905.7632712242427,
			"strokeColor": "#1971c2",
			"backgroundColor": "transparent",
			"width": 0.06696714985918106,
			"height": 38.977925179402064,
			"seed": 200714589,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029726,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-0.06696714985918106,
					-38.977925179402064
				]
			]
		},
		{
			"type": "text",
			"version": 159,
			"versionNonce": 1356568450,
			"isDeleted": false,
			"id": "uzdn8Bcv",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 72.94204821581519,
			"y": 838.2055928617552,
			"strokeColor": "#1971c2",
			"backgroundColor": "transparent",
			"width": 164.0625,
			"height": 24,
			"seed": 1854087411,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029726,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 3,
			"text": "virtual memory",
			"rawText": "virtual memory",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "virtual memory",
			"lineHeight": 1.2,
			"baseline": 20
		},
		{
			"type": "text",
			"version": 288,
			"versionNonce": 1844255134,
			"isDeleted": false,
			"id": "7JcvmDBH",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -13.628212783965978,
			"y": 1012.2532153457738,
			"strokeColor": "#1971c2",
			"backgroundColor": "transparent",
			"width": 517.8685913085938,
			"height": 48,
			"seed": 500003155,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029726,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 3,
			"text": "가상메모리: 램을 이야기하는 것이지만\n2차 메모리(HDD)를 포함해서 virtual memory라고 하자.",
			"rawText": "가상메모리: 램을 이야기하는 것이지만\n2차 메모리(HDD)를 포함해서 virtual memory라고 하자.",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "가상메모리: 램을 이야기하는 것이지만\n2차 메모리(HDD)를 포함해서 virtual memory라고 하자.",
			"lineHeight": 1.2,
			"baseline": 44
		},
		{
			"type": "rectangle",
			"version": 235,
			"versionNonce": 104945474,
			"isDeleted": false,
			"id": "hgKMtmzkMIQ0uBqLdQ-vm",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 400.904610640388,
			"y": 660.7896742998275,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffffff",
			"width": 127,
			"height": 83,
			"seed": 172049811,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"type": "text",
					"id": "SqWX0sQZ"
				}
			],
			"updated": 1700563029726,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 193,
			"versionNonce": 2056533470,
			"isDeleted": false,
			"id": "SqWX0sQZ",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 423.388985640388,
			"y": 678.2896742998275,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 82.03125,
			"height": 48,
			"seed": 1539906355,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029726,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 3,
			"text": "MS-Word\n#2",
			"rawText": "MS-Word\n#2",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "hgKMtmzkMIQ0uBqLdQ-vm",
			"originalText": "MS-Word\n#2",
			"lineHeight": 1.2,
			"baseline": 44
		},
		{
			"type": "text",
			"version": 314,
			"versionNonce": 1348017922,
			"isDeleted": false,
			"id": "UXqozoZG",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -13.566504900428882,
			"y": 1071.817395705241,
			"strokeColor": "#1971c2",
			"backgroundColor": "#ffffff",
			"width": 681.9495849609375,
			"height": 24,
			"seed": 1822532253,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029726,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 3,
			"text": "멀티태스킹 환경에서는 각각의 프로세스가 가상메모리라는 체계를 활용하고 있다.",
			"rawText": "멀티태스킹 환경에서는 각각의 프로세스가 가상메모리라는 체계를 활용하고 있다.",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "멀티태스킹 환경에서는 각각의 프로세스가 가상메모리라는 체계를 활용하고 있다.",
			"lineHeight": 1.2,
			"baseline": 20
		},
		{
			"type": "rectangle",
			"version": 484,
			"versionNonce": 1418578462,
			"isDeleted": false,
			"id": "-ToaJzQgPl9Hw-jvXrj_j",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -348.5272908876058,
			"y": 1457.4692161400171,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 854.4692262229381,
			"height": 1.2251502303088742,
			"seed": 1947362067,
			"groupIds": [
				"LyzHz3rh5DNar5j5ahkod"
			],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [],
			"updated": 1700563029726,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 614,
			"versionNonce": 1537339074,
			"isDeleted": false,
			"id": "5MS8M_4xbdeE9d4iPU3uB",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -348.5272908876058,
			"y": 1584.5204622483739,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 854.4692262229381,
			"height": 1.2251502303088742,
			"seed": 2023393459,
			"groupIds": [
				"LyzHz3rh5DNar5j5ahkod"
			],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [],
			"updated": 1700563029726,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 356,
			"versionNonce": 449500766,
			"isDeleted": false,
			"id": "Sxikb3bF",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -348.5272908876058,
			"y": 1432.712180867413,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 70.3125,
			"height": 48,
			"seed": 810351187,
			"groupIds": [
				"LyzHz3rh5DNar5j5ahkod"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029726,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 3,
			"text": "User\nKernel",
			"rawText": "User\nKernel",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "User\nKernel",
			"lineHeight": 1.2,
			"baseline": 44
		},
		{
			"type": "text",
			"version": 423,
			"versionNonce": 1824179842,
			"isDeleted": false,
			"id": "5tjdZqfg",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -348.5272908876058,
			"y": 1559.202693844373,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 35.15625,
			"height": 48,
			"seed": 1476409331,
			"groupIds": [
				"LyzHz3rh5DNar5j5ahkod"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029726,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 3,
			"text": "S/W\nH/W",
			"rawText": "S/W\nH/W",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "S/W\nH/W",
			"lineHeight": 1.2,
			"baseline": 44
		},
		{
			"type": "text",
			"version": 273,
			"versionNonce": 1713134238,
			"isDeleted": false,
			"id": "DECbSRZS",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -379.6110009233421,
			"y": 1157.2000958089357,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffffff",
			"width": 188.01470947265625,
			"height": 55.773495002216784,
			"seed": 444192925,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029726,
			"link": null,
			"locked": false,
			"fontSize": 46.47791250184732,
			"fontFamily": 3,
			"text": "가상 머신",
			"rawText": "가상 머신",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "가상 머신",
			"lineHeight": 1.2,
			"baseline": 45
		},
		{
			"type": "rectangle",
			"version": 288,
			"versionNonce": 1549968962,
			"isDeleted": false,
			"id": "9e87YcLePM7SwfF_kx3Qr",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -215.58560122771928,
			"y": 1457.7987762683729,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 139,
			"height": 73,
			"seed": 335286771,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"type": "text",
					"id": "allNpC3v"
				}
			],
			"updated": 1700563029726,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 291,
			"versionNonce": 221468382,
			"isDeleted": false,
			"id": "allNpC3v",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -181.24185122771928,
			"y": 1482.2987762683729,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 70.3125,
			"height": 24,
			"seed": 288054163,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029726,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 3,
			"text": "TCP/IP",
			"rawText": "TCP/IP",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "9e87YcLePM7SwfF_kx3Qr",
			"originalText": "TCP/IP",
			"lineHeight": 1.2,
			"baseline": 20
		},
		{
			"type": "rectangle",
			"version": 332,
			"versionNonce": 326667778,
			"isDeleted": false,
			"id": "wsXS8zlbhcObwnLsaRmQH",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -215.58560122771928,
			"y": 1551.3283000218921,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 139,
			"height": 34,
			"seed": 1761636659,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"type": "text",
					"id": "fdMCbK07"
				}
			],
			"updated": 1700563029726,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 328,
			"versionNonce": 1755368222,
			"isDeleted": false,
			"id": "fdMCbK07",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -181.24185122771928,
			"y": 1556.3283000218921,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 70.3125,
			"height": 24,
			"seed": 1558303443,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029726,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 3,
			"text": "driver",
			"rawText": "driver",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "wsXS8zlbhcObwnLsaRmQH",
			"originalText": "driver",
			"lineHeight": 1.2,
			"baseline": 20
		},
		{
			"type": "rectangle",
			"version": 402,
			"versionNonce": 117145026,
			"isDeleted": false,
			"id": "x0oixotuTO14sWEmTuSYU",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -215.58560122771928,
			"y": 1585.8963754922588,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 139,
			"height": 34,
			"seed": 1297040573,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"type": "text",
					"id": "09xemSwa"
				},
				{
					"id": "OMwWppUGw5FH6Aep86f-w",
					"type": "arrow"
				},
				{
					"id": "EmwoIgJQBLVi5B0KkY3MH",
					"type": "arrow"
				}
			],
			"updated": 1700563029726,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 399,
			"versionNonce": 383104862,
			"isDeleted": false,
			"id": "09xemSwa",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -163.66372622771928,
			"y": 1590.8963754922588,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 35.15625,
			"height": 24,
			"seed": 1944167709,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029726,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 3,
			"text": "NIC",
			"rawText": "NIC",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "x0oixotuTO14sWEmTuSYU",
			"originalText": "NIC",
			"lineHeight": 1.2,
			"baseline": 20
		},
		{
			"type": "rectangle",
			"version": 339,
			"versionNonce": 873100674,
			"isDeleted": false,
			"id": "2TvWuL_nBqBvKXEZGnheU",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -215.58560122771928,
			"y": 1350.2464660817031,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 139,
			"height": 73,
			"seed": 102910269,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"type": "text",
					"id": "pc1aVbNM"
				}
			],
			"updated": 1700563029726,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 337,
			"versionNonce": 1076042654,
			"isDeleted": false,
			"id": "pc1aVbNM",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -187.10122622771928,
			"y": 1374.7464660817031,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 82.03125,
			"height": 24,
			"seed": 350230941,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029726,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 3,
			"text": "process",
			"rawText": "process",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "2TvWuL_nBqBvKXEZGnheU",
			"originalText": "process",
			"lineHeight": 1.2,
			"baseline": 20
		},
		{
			"type": "ellipse",
			"version": 233,
			"versionNonce": 467957058,
			"isDeleted": false,
			"id": "RKsSS5NsEHd34fOpbO3Wa",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -162.6953658206263,
			"y": 1424.7170173061388,
			"strokeColor": "#1971c2",
			"backgroundColor": "#ffffff",
			"width": 33.219529185814054,
			"height": 33.219529185814054,
			"seed": 1897241437,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029726,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 235,
			"versionNonce": 1522137054,
			"isDeleted": false,
			"id": "K4Sibamq",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -161.75352127039056,
			"y": 1432.0316757867668,
			"strokeColor": "#1971c2",
			"backgroundColor": "#ffffff",
			"width": 31.3125,
			"height": 16.0439501236954,
			"seed": 589251133,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029726,
			"link": null,
			"locked": false,
			"fontSize": 13.369958436412833,
			"fontFamily": 3,
			"text": "file",
			"rawText": "file",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "file",
			"lineHeight": 1.2,
			"baseline": 13
		},
		{
			"type": "text",
			"version": 265,
			"versionNonce": 1072200962,
			"isDeleted": false,
			"id": "EXGIvJDF",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -203.08280486104613,
			"y": 1423.8379585128152,
			"strokeColor": "#1971c2",
			"backgroundColor": "#ffffff",
			"width": 35.71875,
			"height": 12.195227779101076,
			"seed": 1835761811,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029726,
			"link": null,
			"locked": false,
			"fontSize": 10.162689815917563,
			"fontFamily": 3,
			"text": "socket",
			"rawText": "socket",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "socket",
			"lineHeight": 1.2,
			"baseline": 10
		},
		{
			"type": "rectangle",
			"version": 275,
			"versionNonce": 1856719902,
			"isDeleted": false,
			"id": "Ps965qIn6s0_w99_9SBLC",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 8.278088890460339,
			"y": 1551.4386680532791,
			"strokeColor": "#1971c2",
			"backgroundColor": "transparent",
			"width": 86,
			"height": 34,
			"seed": 633741491,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"type": "text",
					"id": "zIExxQLw"
				},
				{
					"id": "vxz3CiqK6PO8wkt9YtCzp",
					"type": "arrow"
				}
			],
			"updated": 1700563029726,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 237,
			"versionNonce": 496340162,
			"isDeleted": false,
			"id": "zIExxQLw",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 16.12183889046034,
			"y": 1556.4386680532791,
			"strokeColor": "#1971c2",
			"backgroundColor": "#ffffff",
			"width": 70.3125,
			"height": 24,
			"seed": 1303352499,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029726,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 3,
			"text": "VMware",
			"rawText": "VMware",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "Ps965qIn6s0_w99_9SBLC",
			"originalText": "VMware",
			"lineHeight": 1.2,
			"baseline": 20
		},
		{
			"type": "rectangle",
			"version": 334,
			"versionNonce": 1508382814,
			"isDeleted": false,
			"id": "GvDji3AvOKpVC7dgGfcy2",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 156.39882979651375,
			"y": 1551.4386680532791,
			"strokeColor": "#1971c2",
			"backgroundColor": "transparent",
			"width": 86,
			"height": 34,
			"seed": 1006153267,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"type": "text",
					"id": "a0oDntb3"
				}
			],
			"updated": 1700563029726,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 295,
			"versionNonce": 713729154,
			"isDeleted": false,
			"id": "a0oDntb3",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 164.24257979651375,
			"y": 1556.4386680532791,
			"strokeColor": "#1971c2",
			"backgroundColor": "#ffffff",
			"width": 70.3125,
			"height": 24,
			"seed": 2143973331,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029726,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 3,
			"text": "VMware",
			"rawText": "VMware",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "GvDji3AvOKpVC7dgGfcy2",
			"originalText": "VMware",
			"lineHeight": 1.2,
			"baseline": 20
		},
		{
			"type": "rectangle",
			"version": 320,
			"versionNonce": 339827870,
			"isDeleted": false,
			"id": "mSUtRdLS9Nrgvn1D5iYWb",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 304.5195707025672,
			"y": 1550.4065788821247,
			"strokeColor": "#1971c2",
			"backgroundColor": "transparent",
			"width": 86,
			"height": 34,
			"seed": 1732585875,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"type": "text",
					"id": "TbH69g8F"
				}
			],
			"updated": 1700563029726,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 281,
			"versionNonce": 1351009346,
			"isDeleted": false,
			"id": "TbH69g8F",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 312.3633207025672,
			"y": 1555.4065788821247,
			"strokeColor": "#1971c2",
			"backgroundColor": "#ffffff",
			"width": 70.3125,
			"height": 24,
			"seed": 917536563,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029726,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 3,
			"text": "VMware",
			"rawText": "VMware",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "mSUtRdLS9Nrgvn1D5iYWb",
			"originalText": "VMware",
			"lineHeight": 1.2,
			"baseline": 20
		},
		{
			"type": "text",
			"version": 114,
			"versionNonce": 1936201950,
			"isDeleted": false,
			"id": "lKyWESJt",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 4.403088890460339,
			"y": 1266.8262873551328,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 93.75,
			"height": 24,
			"seed": 1836516819,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029726,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 3,
			"text": "Linux #1",
			"rawText": "Linux #1",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Linux #1",
			"lineHeight": 1.2,
			"baseline": 20
		},
		{
			"type": "text",
			"version": 168,
			"versionNonce": 1768483842,
			"isDeleted": false,
			"id": "aYMe5k6f",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 152.52382979651375,
			"y": 1266.8262873551328,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 93.75,
			"height": 24,
			"seed": 1723352467,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029726,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 3,
			"text": "Linux #2",
			"rawText": "Linux #2",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Linux #2",
			"lineHeight": 1.2,
			"baseline": 20
		},
		{
			"type": "text",
			"version": 137,
			"versionNonce": 1861045534,
			"isDeleted": false,
			"id": "cwSPrBwu",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 300.6445707025672,
			"y": 1266.8262873551328,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 93.75,
			"height": 24,
			"seed": 156376349,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029726,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 3,
			"text": "Linux #3",
			"rawText": "Linux #3",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Linux #3",
			"lineHeight": 1.2,
			"baseline": 20
		},
		{
			"type": "rectangle",
			"version": 525,
			"versionNonce": 993008578,
			"isDeleted": false,
			"id": "UEbZZuSzrcVUlCJEEGtPn",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 10.865273821634105,
			"y": 1378.0393872493455,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 87,
			"height": 46,
			"seed": 1285364691,
			"groupIds": [
				"Dbd7N2ZNPnLaZCSWLShcM",
				"c-o9vadpfDEClwe9iB5Yn"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"type": "text",
					"id": "QufTEwS0"
				}
			],
			"updated": 1700563029726,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 635,
			"versionNonce": 1682045278,
			"isDeleted": false,
			"id": "QufTEwS0",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 33.412148821634105,
			"y": 1393.883915638783,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 41.90625,
			"height": 14.310943221125004,
			"seed": 147859827,
			"groupIds": [
				"Dbd7N2ZNPnLaZCSWLShcM",
				"c-o9vadpfDEClwe9iB5Yn"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029726,
			"link": null,
			"locked": false,
			"fontSize": 11.925786017604171,
			"fontFamily": 3,
			"text": "TCP/IP",
			"rawText": "TCP/IP",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "UEbZZuSzrcVUlCJEEGtPn",
			"originalText": "TCP/IP",
			"lineHeight": 1.2,
			"baseline": 11
		},
		{
			"type": "rectangle",
			"version": 621,
			"versionNonce": 1945850754,
			"isDeleted": false,
			"id": "VDtsp7V2Kv-RN3_K6pvWo",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 10.865273821634105,
			"y": 1432.9631739159247,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 87,
			"height": 25,
			"seed": 311460627,
			"groupIds": [
				"Dbd7N2ZNPnLaZCSWLShcM",
				"c-o9vadpfDEClwe9iB5Yn"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"type": "text",
					"id": "BmduPOZ6"
				}
			],
			"updated": 1700563029726,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 672,
			"versionNonce": 1521950110,
			"isDeleted": false,
			"id": "BmduPOZ6",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 33.412148821634105,
			"y": 1438.3077023053622,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 41.90625,
			"height": 14.310943221125004,
			"seed": 1649715379,
			"groupIds": [
				"Dbd7N2ZNPnLaZCSWLShcM",
				"c-o9vadpfDEClwe9iB5Yn"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029726,
			"link": null,
			"locked": false,
			"fontSize": 11.925786017604171,
			"fontFamily": 3,
			"text": "driver",
			"rawText": "driver",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "VDtsp7V2Kv-RN3_K6pvWo",
			"originalText": "driver",
			"lineHeight": 1.2,
			"baseline": 11
		},
		{
			"type": "rectangle",
			"version": 762,
			"versionNonce": 638161730,
			"isDeleted": false,
			"id": "EFqaVI65nmRIBeFePX29t",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 10.97252486489056,
			"y": 1458.1379987273854,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 87,
			"height": 25,
			"seed": 499325523,
			"groupIds": [
				"Dbd7N2ZNPnLaZCSWLShcM",
				"c-o9vadpfDEClwe9iB5Yn"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"type": "text",
					"id": "2hLh5SxK"
				}
			],
			"updated": 1700563029726,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 816,
			"versionNonce": 1199421918,
			"isDeleted": false,
			"id": "2hLh5SxK",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 43.99596236489056,
			"y": 1463.482527116823,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 20.953125,
			"height": 14.310943221125004,
			"seed": 1907513331,
			"groupIds": [
				"Dbd7N2ZNPnLaZCSWLShcM",
				"c-o9vadpfDEClwe9iB5Yn"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029726,
			"link": null,
			"locked": false,
			"fontSize": 11.925786017604171,
			"fontFamily": 3,
			"text": "NIC",
			"rawText": "NIC",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "EFqaVI65nmRIBeFePX29t",
			"originalText": "NIC",
			"lineHeight": 1.2,
			"baseline": 11
		},
		{
			"type": "rectangle",
			"version": 576,
			"versionNonce": 1136253698,
			"isDeleted": false,
			"id": "Ugxe7VZZXgEGNh66d_-sQ",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 10.865273821634105,
			"y": 1310.7833530736525,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 87,
			"height": 46,
			"seed": 740876691,
			"groupIds": [
				"Dbd7N2ZNPnLaZCSWLShcM",
				"c-o9vadpfDEClwe9iB5Yn"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"type": "text",
					"id": "I9StjEoo"
				}
			],
			"updated": 1700563029726,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 681,
			"versionNonce": 1369886238,
			"isDeleted": false,
			"id": "I9StjEoo",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 29.919961321634105,
			"y": 1326.62788146309,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 48.890625,
			"height": 14.310943221125004,
			"seed": 375207731,
			"groupIds": [
				"Dbd7N2ZNPnLaZCSWLShcM",
				"c-o9vadpfDEClwe9iB5Yn"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029726,
			"link": null,
			"locked": false,
			"fontSize": 11.925786017604171,
			"fontFamily": 3,
			"text": "process",
			"rawText": "process",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "Ugxe7VZZXgEGNh66d_-sQ",
			"originalText": "process",
			"lineHeight": 1.2,
			"baseline": 11
		},
		{
			"type": "ellipse",
			"version": 469,
			"versionNonce": 462105282,
			"isDeleted": false,
			"id": "vtZhEJI1lfqRRw8eSP2RA",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 43.978635978412534,
			"y": 1357.5276007461407,
			"strokeColor": "#1971c2",
			"backgroundColor": "#ffffff",
			"width": 20.773275686443146,
			"height": 20.773275686443146,
			"seed": 246798547,
			"groupIds": [
				"Dbd7N2ZNPnLaZCSWLShcM",
				"c-o9vadpfDEClwe9iB5Yn"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029726,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 471,
			"versionNonce": 371415646,
			"isDeleted": false,
			"id": "7jdRyok8",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 44.5676026788851,
			"y": 1362.1016998045689,
			"strokeColor": "#1971c2",
			"backgroundColor": "#ffffff",
			"width": 19.59375,
			"height": 10.03281525017498,
			"seed": 1657357939,
			"groupIds": [
				"Dbd7N2ZNPnLaZCSWLShcM",
				"c-o9vadpfDEClwe9iB5Yn"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029726,
			"link": null,
			"locked": false,
			"fontSize": 8.360679375145818,
			"fontFamily": 3,
			"text": "file",
			"rawText": "file",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "file",
			"lineHeight": 1.2,
			"baseline": 8
		},
		{
			"type": "text",
			"version": 501,
			"versionNonce": 1411154562,
			"isDeleted": false,
			"id": "dHbVYVGA",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 18.72302802674018,
			"y": 1356.977896066217,
			"strokeColor": "#1971c2",
			"backgroundColor": "#ffffff",
			"width": 22.32421875,
			"height": 7.626081251699966,
			"seed": 1767768083,
			"groupIds": [
				"Dbd7N2ZNPnLaZCSWLShcM",
				"c-o9vadpfDEClwe9iB5Yn"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029726,
			"link": null,
			"locked": false,
			"fontSize": 6.355067709749972,
			"fontFamily": 3,
			"text": "socket",
			"rawText": "socket",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "socket",
			"lineHeight": 1.2,
			"baseline": 6
		},
		{
			"type": "rectangle",
			"version": 150,
			"versionNonce": 1808031390,
			"isDeleted": false,
			"id": "XsvVjWiiqymYdDxwUDYK4",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -14.534297738262126,
			"y": 1298.9326759533196,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 131.38616133871557,
			"height": 196.40085808536514,
			"seed": 181189661,
			"groupIds": [
				"c-o9vadpfDEClwe9iB5Yn"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029726,
			"link": null,
			"locked": false
		},
		{
			"type": "line",
			"version": 238,
			"versionNonce": 1747771970,
			"isDeleted": false,
			"id": "mJD9QTEQbkG20sDXEGYDu",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -13.559555652450456,
			"y": 1377.7813519355423,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 130.65003117163326,
			"height": 0.005628918007460015,
			"seed": 1699057203,
			"groupIds": [
				"c-o9vadpfDEClwe9iB5Yn"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029726,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					130.65003117163326,
					-0.005628918007460015
				]
			]
		},
		{
			"type": "text",
			"version": 178,
			"versionNonce": 658168542,
			"isDeleted": false,
			"id": "KhxmL1kB",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -11.806110549617557,
			"y": 1363.962137829012,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 6.474609375,
			"height": 26.531452368043578,
			"seed": 1608740221,
			"groupIds": [
				"c-o9vadpfDEClwe9iB5Yn"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029726,
			"link": null,
			"locked": false,
			"fontSize": 11.054771820018157,
			"fontFamily": 3,
			"text": "U\nK",
			"rawText": "U\nK",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "U\nK",
			"lineHeight": 1.2,
			"baseline": 24
		},
		{
			"type": "text",
			"version": 237,
			"versionNonce": 580602370,
			"isDeleted": false,
			"id": "UMRuPxzt",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -11.806110549617557,
			"y": 1444.331333114575,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 19.423828125,
			"height": 26.531452368043578,
			"seed": 145956435,
			"groupIds": [
				"c-o9vadpfDEClwe9iB5Yn"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029726,
			"link": null,
			"locked": false,
			"fontSize": 11.054771820018157,
			"fontFamily": 3,
			"text": "S/W\nH/W",
			"rawText": "S/W\nH/W",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "S/W\nH/W",
			"lineHeight": 1.2,
			"baseline": 24
		},
		{
			"type": "rectangle",
			"version": 612,
			"versionNonce": 1595395870,
			"isDeleted": false,
			"id": "jcRcqH-zW-idXNAUKQLUd",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 158.98601472768752,
			"y": 1377.7913328980094,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 87,
			"height": 46,
			"seed": 418789203,
			"groupIds": [
				"ziWs1UNgtpzEjkdZUkiqV",
				"fYWgTZppHSGTglJkAZqwp"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"type": "text",
					"id": "yHR6Ms9k"
				}
			],
			"updated": 1700563029727,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 722,
			"versionNonce": 442939842,
			"isDeleted": false,
			"id": "yHR6Ms9k",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 181.53288972768752,
			"y": 1393.635861287447,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 41.90625,
			"height": 14.310943221125004,
			"seed": 846845171,
			"groupIds": [
				"ziWs1UNgtpzEjkdZUkiqV",
				"fYWgTZppHSGTglJkAZqwp"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029727,
			"link": null,
			"locked": false,
			"fontSize": 11.925786017604171,
			"fontFamily": 3,
			"text": "TCP/IP",
			"rawText": "TCP/IP",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "jcRcqH-zW-idXNAUKQLUd",
			"originalText": "TCP/IP",
			"lineHeight": 1.2,
			"baseline": 11
		},
		{
			"type": "rectangle",
			"version": 708,
			"versionNonce": 801913694,
			"isDeleted": false,
			"id": "DfK9dCIIndNtQIMx6J3cT",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 158.98601472768752,
			"y": 1432.7151195645883,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 87,
			"height": 25,
			"seed": 1090043539,
			"groupIds": [
				"ziWs1UNgtpzEjkdZUkiqV",
				"fYWgTZppHSGTglJkAZqwp"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"type": "text",
					"id": "kc1HKtIa"
				}
			],
			"updated": 1700563029727,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 760,
			"versionNonce": 783167874,
			"isDeleted": false,
			"id": "kc1HKtIa",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 181.53288972768752,
			"y": 1438.0596479540259,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 41.90625,
			"height": 14.310943221125004,
			"seed": 522810419,
			"groupIds": [
				"ziWs1UNgtpzEjkdZUkiqV",
				"fYWgTZppHSGTglJkAZqwp"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029727,
			"link": null,
			"locked": false,
			"fontSize": 11.925786017604171,
			"fontFamily": 3,
			"text": "driver",
			"rawText": "driver",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "DfK9dCIIndNtQIMx6J3cT",
			"originalText": "driver",
			"lineHeight": 1.2,
			"baseline": 11
		},
		{
			"type": "rectangle",
			"version": 850,
			"versionNonce": 2141790110,
			"isDeleted": false,
			"id": "Pf2UXNAJaQTwTZz6R-Frz",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 159.09326577094396,
			"y": 1457.8899443760492,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 87,
			"height": 25,
			"seed": 217216467,
			"groupIds": [
				"ziWs1UNgtpzEjkdZUkiqV",
				"fYWgTZppHSGTglJkAZqwp"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"type": "text",
					"id": "5dDTeVbu"
				}
			],
			"updated": 1700563029727,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 903,
			"versionNonce": 45134146,
			"isDeleted": false,
			"id": "5dDTeVbu",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 192.11670327094396,
			"y": 1463.2344727654868,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 20.953125,
			"height": 14.310943221125004,
			"seed": 157959027,
			"groupIds": [
				"ziWs1UNgtpzEjkdZUkiqV",
				"fYWgTZppHSGTglJkAZqwp"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029727,
			"link": null,
			"locked": false,
			"fontSize": 11.925786017604171,
			"fontFamily": 3,
			"text": "NIC",
			"rawText": "NIC",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "Pf2UXNAJaQTwTZz6R-Frz",
			"originalText": "NIC",
			"lineHeight": 1.2,
			"baseline": 11
		},
		{
			"type": "rectangle",
			"version": 663,
			"versionNonce": 1121942494,
			"isDeleted": false,
			"id": "WapIP8TPm0Z5s92knVM1o",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 158.98601472768752,
			"y": 1310.5352987223164,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 87,
			"height": 46,
			"seed": 1826053395,
			"groupIds": [
				"ziWs1UNgtpzEjkdZUkiqV",
				"fYWgTZppHSGTglJkAZqwp"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"type": "text",
					"id": "jQRB7zHA"
				}
			],
			"updated": 1700563029727,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 768,
			"versionNonce": 2043492610,
			"isDeleted": false,
			"id": "jQRB7zHA",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 178.04070222768752,
			"y": 1326.379827111754,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 48.890625,
			"height": 14.310943221125004,
			"seed": 1118847667,
			"groupIds": [
				"ziWs1UNgtpzEjkdZUkiqV",
				"fYWgTZppHSGTglJkAZqwp"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029727,
			"link": null,
			"locked": false,
			"fontSize": 11.925786017604171,
			"fontFamily": 3,
			"text": "process",
			"rawText": "process",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "WapIP8TPm0Z5s92knVM1o",
			"originalText": "process",
			"lineHeight": 1.2,
			"baseline": 11
		},
		{
			"type": "ellipse",
			"version": 556,
			"versionNonce": 1065373726,
			"isDeleted": false,
			"id": "oxjsHAU_tYLhM1Y10OzgU",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 192.09937688446595,
			"y": 1357.2795463948046,
			"strokeColor": "#1971c2",
			"backgroundColor": "#ffffff",
			"width": 20.773275686443146,
			"height": 20.773275686443146,
			"seed": 1671132243,
			"groupIds": [
				"ziWs1UNgtpzEjkdZUkiqV",
				"fYWgTZppHSGTglJkAZqwp"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029727,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 558,
			"versionNonce": 864209090,
			"isDeleted": false,
			"id": "PXUKW4Sw",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 192.6883435849385,
			"y": 1361.8536454532327,
			"strokeColor": "#1971c2",
			"backgroundColor": "#ffffff",
			"width": 19.59375,
			"height": 10.03281525017498,
			"seed": 1332703731,
			"groupIds": [
				"ziWs1UNgtpzEjkdZUkiqV",
				"fYWgTZppHSGTglJkAZqwp"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029727,
			"link": null,
			"locked": false,
			"fontSize": 8.360679375145818,
			"fontFamily": 3,
			"text": "file",
			"rawText": "file",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "file",
			"lineHeight": 1.2,
			"baseline": 8
		},
		{
			"type": "text",
			"version": 588,
			"versionNonce": 1367120990,
			"isDeleted": false,
			"id": "q7zMgN7i",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 166.84376893279358,
			"y": 1356.7298417148809,
			"strokeColor": "#1971c2",
			"backgroundColor": "#ffffff",
			"width": 22.32421875,
			"height": 7.626081251699966,
			"seed": 1194507155,
			"groupIds": [
				"ziWs1UNgtpzEjkdZUkiqV",
				"fYWgTZppHSGTglJkAZqwp"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029727,
			"link": null,
			"locked": false,
			"fontSize": 6.355067709749972,
			"fontFamily": 3,
			"text": "socket",
			"rawText": "socket",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "socket",
			"lineHeight": 1.2,
			"baseline": 6
		},
		{
			"type": "rectangle",
			"version": 237,
			"versionNonce": 124805250,
			"isDeleted": false,
			"id": "KOIqkpmMZxfFGAEL65k8g",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 133.5864431677913,
			"y": 1298.6846216019835,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 131.38616133871557,
			"height": 196.40085808536514,
			"seed": 656134451,
			"groupIds": [
				"fYWgTZppHSGTglJkAZqwp"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029727,
			"link": null,
			"locked": false
		},
		{
			"type": "line",
			"version": 325,
			"versionNonce": 782590110,
			"isDeleted": false,
			"id": "sPl6nf8bKnlwzkviwatcH",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 134.56118525360296,
			"y": 1377.5332975842061,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 130.65003117163326,
			"height": 0.005628918007460015,
			"seed": 9515731,
			"groupIds": [
				"fYWgTZppHSGTglJkAZqwp"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029727,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					130.65003117163326,
					-0.005628918007460015
				]
			]
		},
		{
			"type": "text",
			"version": 265,
			"versionNonce": 22347842,
			"isDeleted": false,
			"id": "2BHqKM1m",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 136.31463035643586,
			"y": 1363.7140834776756,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 6.474609375,
			"height": 26.531452368043578,
			"seed": 1948868723,
			"groupIds": [
				"fYWgTZppHSGTglJkAZqwp"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029727,
			"link": null,
			"locked": false,
			"fontSize": 11.054771820018157,
			"fontFamily": 3,
			"text": "U\nK",
			"rawText": "U\nK",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "U\nK",
			"lineHeight": 1.2,
			"baseline": 24
		},
		{
			"type": "text",
			"version": 324,
			"versionNonce": 715889886,
			"isDeleted": false,
			"id": "HzqEcJDf",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 136.31463035643586,
			"y": 1444.083278763239,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 19.423828125,
			"height": 26.531452368043578,
			"seed": 1269488147,
			"groupIds": [
				"fYWgTZppHSGTglJkAZqwp"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029727,
			"link": null,
			"locked": false,
			"fontSize": 11.054771820018157,
			"fontFamily": 3,
			"text": "S/W\nH/W",
			"rawText": "S/W\nH/W",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "S/W\nH/W",
			"lineHeight": 1.2,
			"baseline": 24
		},
		{
			"type": "rectangle",
			"version": 659,
			"versionNonce": 1561307138,
			"isDeleted": false,
			"id": "v0Z8DUqNvLVmcb-nYCOwV",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 307.10675563374093,
			"y": 1378.0285676580902,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 87,
			"height": 46,
			"seed": 154790419,
			"groupIds": [
				"fy1baJ_5mmhPSF-5WHiyA",
				"4dJQwByQIIo2PJ9DspuPc"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"type": "text",
					"id": "FFejlAGg"
				}
			],
			"updated": 1700563029727,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 770,
			"versionNonce": 2065715486,
			"isDeleted": false,
			"id": "FFejlAGg",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 329.65363063374093,
			"y": 1393.8730960475277,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 41.90625,
			"height": 14.310943221125004,
			"seed": 758722483,
			"groupIds": [
				"fy1baJ_5mmhPSF-5WHiyA",
				"4dJQwByQIIo2PJ9DspuPc"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029727,
			"link": null,
			"locked": false,
			"fontSize": 11.925786017604171,
			"fontFamily": 3,
			"text": "TCP/IP",
			"rawText": "TCP/IP",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "v0Z8DUqNvLVmcb-nYCOwV",
			"originalText": "TCP/IP",
			"lineHeight": 1.2,
			"baseline": 11
		},
		{
			"type": "rectangle",
			"version": 755,
			"versionNonce": 43997122,
			"isDeleted": false,
			"id": "YLZKs-rPfj8sUUPBImXcd",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 307.10675563374093,
			"y": 1432.9523543246692,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 87,
			"height": 25,
			"seed": 1216266579,
			"groupIds": [
				"fy1baJ_5mmhPSF-5WHiyA",
				"4dJQwByQIIo2PJ9DspuPc"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"type": "text",
					"id": "uapq01B3"
				}
			],
			"updated": 1700563029727,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 808,
			"versionNonce": 2071231838,
			"isDeleted": false,
			"id": "uapq01B3",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 329.65363063374093,
			"y": 1438.2968827141067,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 41.90625,
			"height": 14.310943221125004,
			"seed": 878780147,
			"groupIds": [
				"fy1baJ_5mmhPSF-5WHiyA",
				"4dJQwByQIIo2PJ9DspuPc"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029727,
			"link": null,
			"locked": false,
			"fontSize": 11.925786017604171,
			"fontFamily": 3,
			"text": "driver",
			"rawText": "driver",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "YLZKs-rPfj8sUUPBImXcd",
			"originalText": "driver",
			"lineHeight": 1.2,
			"baseline": 11
		},
		{
			"type": "rectangle",
			"version": 897,
			"versionNonce": 35852162,
			"isDeleted": false,
			"id": "bLHdbaJjl-LyZmlfY273W",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 307.21400667699737,
			"y": 1458.12717913613,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 87,
			"height": 25,
			"seed": 1533462675,
			"groupIds": [
				"fy1baJ_5mmhPSF-5WHiyA",
				"4dJQwByQIIo2PJ9DspuPc"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"type": "text",
					"id": "qySRzfm5"
				}
			],
			"updated": 1700563029727,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 951,
			"versionNonce": 1895375262,
			"isDeleted": false,
			"id": "qySRzfm5",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 340.23744417699737,
			"y": 1463.4717075255676,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 20.953125,
			"height": 14.310943221125004,
			"seed": 323370547,
			"groupIds": [
				"fy1baJ_5mmhPSF-5WHiyA",
				"4dJQwByQIIo2PJ9DspuPc"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029727,
			"link": null,
			"locked": false,
			"fontSize": 11.925786017604171,
			"fontFamily": 3,
			"text": "NIC",
			"rawText": "NIC",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "bLHdbaJjl-LyZmlfY273W",
			"originalText": "NIC",
			"lineHeight": 1.2,
			"baseline": 11
		},
		{
			"type": "rectangle",
			"version": 710,
			"versionNonce": 265932610,
			"isDeleted": false,
			"id": "H4FdN8LhL_qkQ90cyFabs",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 307.10675563374093,
			"y": 1310.7725334823967,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 87,
			"height": 46,
			"seed": 921042899,
			"groupIds": [
				"fy1baJ_5mmhPSF-5WHiyA",
				"4dJQwByQIIo2PJ9DspuPc"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"type": "text",
					"id": "pNI5DcYe"
				}
			],
			"updated": 1700563029727,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 816,
			"versionNonce": 1323253214,
			"isDeleted": false,
			"id": "pNI5DcYe",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 326.16144313374093,
			"y": 1326.6170618718343,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 48.890625,
			"height": 14.310943221125004,
			"seed": 6065523,
			"groupIds": [
				"fy1baJ_5mmhPSF-5WHiyA",
				"4dJQwByQIIo2PJ9DspuPc"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029727,
			"link": null,
			"locked": false,
			"fontSize": 11.925786017604171,
			"fontFamily": 3,
			"text": "process",
			"rawText": "process",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "H4FdN8LhL_qkQ90cyFabs",
			"originalText": "process",
			"lineHeight": 1.2,
			"baseline": 11
		},
		{
			"type": "ellipse",
			"version": 603,
			"versionNonce": 2266882,
			"isDeleted": false,
			"id": "4ow_xtooE1ciTjdtKE-Lv",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 340.2201177905194,
			"y": 1357.516781154885,
			"strokeColor": "#1971c2",
			"backgroundColor": "#ffffff",
			"width": 20.773275686443146,
			"height": 20.773275686443146,
			"seed": 586180371,
			"groupIds": [
				"fy1baJ_5mmhPSF-5WHiyA",
				"4dJQwByQIIo2PJ9DspuPc"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029727,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 605,
			"versionNonce": 2050478622,
			"isDeleted": false,
			"id": "uvFJqCBO",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 340.8090844909919,
			"y": 1362.090880213313,
			"strokeColor": "#1971c2",
			"backgroundColor": "#ffffff",
			"width": 19.59375,
			"height": 10.03281525017498,
			"seed": 622333107,
			"groupIds": [
				"fy1baJ_5mmhPSF-5WHiyA",
				"4dJQwByQIIo2PJ9DspuPc"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029727,
			"link": null,
			"locked": false,
			"fontSize": 8.360679375145818,
			"fontFamily": 3,
			"text": "file",
			"rawText": "file",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "file",
			"lineHeight": 1.2,
			"baseline": 8
		},
		{
			"type": "text",
			"version": 635,
			"versionNonce": 1132226242,
			"isDeleted": false,
			"id": "ecZM5yYR",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 314.964509838847,
			"y": 1356.9670764749612,
			"strokeColor": "#1971c2",
			"backgroundColor": "#ffffff",
			"width": 22.32421875,
			"height": 7.626081251699966,
			"seed": 2054815315,
			"groupIds": [
				"fy1baJ_5mmhPSF-5WHiyA",
				"4dJQwByQIIo2PJ9DspuPc"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029727,
			"link": null,
			"locked": false,
			"fontSize": 6.355067709749972,
			"fontFamily": 3,
			"text": "socket",
			"rawText": "socket",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "socket",
			"lineHeight": 1.2,
			"baseline": 6
		},
		{
			"type": "rectangle",
			"version": 284,
			"versionNonce": 234085982,
			"isDeleted": false,
			"id": "39WHICeX3rrobEy8zQCg-",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 281.7071840738447,
			"y": 1298.9218563620639,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 131.38616133871557,
			"height": 196.40085808536514,
			"seed": 1575795699,
			"groupIds": [
				"4dJQwByQIIo2PJ9DspuPc"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029727,
			"link": null,
			"locked": false
		},
		{
			"type": "line",
			"version": 372,
			"versionNonce": 1652964994,
			"isDeleted": false,
			"id": "w5NNpCk6_Koo-yHmNNswR",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 282.68192615965637,
			"y": 1377.7705323442865,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 130.65003117163326,
			"height": 0.005628918007460015,
			"seed": 1802945939,
			"groupIds": [
				"4dJQwByQIIo2PJ9DspuPc"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029727,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					130.65003117163326,
					-0.005628918007460015
				]
			]
		},
		{
			"type": "text",
			"version": 312,
			"versionNonce": 518283934,
			"isDeleted": false,
			"id": "gUtjDbFQ",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 284.43537126248924,
			"y": 1363.9513182377564,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 6.474609375,
			"height": 26.531452368043578,
			"seed": 2051971891,
			"groupIds": [
				"4dJQwByQIIo2PJ9DspuPc"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029727,
			"link": null,
			"locked": false,
			"fontSize": 11.054771820018157,
			"fontFamily": 3,
			"text": "U\nK",
			"rawText": "U\nK",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "U\nK",
			"lineHeight": 1.2,
			"baseline": 24
		},
		{
			"type": "text",
			"version": 371,
			"versionNonce": 2046762562,
			"isDeleted": false,
			"id": "5SneuPIj",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 284.43537126248924,
			"y": 1444.3205135233197,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 19.423828125,
			"height": 26.531452368043578,
			"seed": 920304851,
			"groupIds": [
				"4dJQwByQIIo2PJ9DspuPc"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029727,
			"link": null,
			"locked": false,
			"fontSize": 11.054771820018157,
			"fontFamily": 3,
			"text": "S/W\nH/W",
			"rawText": "S/W\nH/W",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "S/W\nH/W",
			"lineHeight": 1.2,
			"baseline": 24
		},
		{
			"type": "rectangle",
			"version": 278,
			"versionNonce": 2142920414,
			"isDeleted": false,
			"id": "qrcxtz74TqLEjEzY2M-iM",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 32.144632281158806,
			"y": 1464.5531672846669,
			"strokeColor": "#e03131",
			"backgroundColor": "transparent",
			"width": 344.34925516498487,
			"height": 13.81883239336275,
			"seed": 983280467,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029727,
			"link": null,
			"locked": false
		},
		{
			"type": "line",
			"version": 114,
			"versionNonce": 918947330,
			"isDeleted": false,
			"id": "n1hge-z3pPMEfHn12ca2J",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 376.8646755017987,
			"y": 1470.0251698948327,
			"strokeColor": "#e03131",
			"backgroundColor": "transparent",
			"width": 127.47048504632653,
			"height": 84.34622205164783,
			"seed": 578675635,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029727,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					127.47048504632653,
					-84.34622205164783
				]
			]
		},
		{
			"type": "text",
			"version": 152,
			"versionNonce": 84333342,
			"isDeleted": false,
			"id": "alsYyXDN",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 450.55707428971454,
			"y": 1346.6817171201465,
			"strokeColor": "#e03131",
			"backgroundColor": "transparent",
			"width": 165.05859375,
			"height": 37.57629563391434,
			"seed": 1459059379,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029727,
			"link": null,
			"locked": false,
			"fontSize": 15.656789847464308,
			"fontFamily": 3,
			"text": "S/W NIC\nvirtual NIC driver",
			"rawText": "S/W NIC\nvirtual NIC driver",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "S/W NIC\nvirtual NIC driver",
			"lineHeight": 1.2,
			"baseline": 34
		},
		{
			"type": "text",
			"version": 258,
			"versionNonce": 1373238722,
			"isDeleted": false,
			"id": "Qt4R7NWi",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -215.7589958155443,
			"y": 1228.0826786337582,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 82.03125,
			"height": 24,
			"seed": 1701632211,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029727,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 3,
			"text": "Host OS",
			"rawText": "Host OS",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Host OS",
			"lineHeight": 1.2,
			"baseline": 20
		},
		{
			"type": "text",
			"version": 143,
			"versionNonce": 1228586846,
			"isDeleted": false,
			"id": "qysbl5Kr",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -17.18502065201102,
			"y": 1227.3312565167691,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 93.75,
			"height": 24,
			"seed": 2142319443,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029727,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 3,
			"text": "Guest OS",
			"rawText": "Guest OS",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Guest OS",
			"lineHeight": 1.2,
			"baseline": 20
		},
		{
			"type": "rectangle",
			"version": 130,
			"versionNonce": 207220098,
			"isDeleted": false,
			"id": "ZYs_5vs5x9A0MECaLVsIT",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "dashed",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -14.181845301502563,
			"y": 1258.202391249527,
			"strokeColor": "#1971c2",
			"backgroundColor": "transparent",
			"width": 425.38282485674205,
			"height": 36.46030793738578,
			"seed": 1247805853,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029727,
			"link": null,
			"locked": false
		},
		{
			"type": "arrow",
			"version": 192,
			"versionNonce": 628398029,
			"isDeleted": false,
			"id": "vxz3CiqK6PO8wkt9YtCzp",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "dashed",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 55.190300088188025,
			"y": 1477.7221054042757,
			"strokeColor": "#e03131",
			"backgroundColor": "transparent",
			"width": 0.3993960478357508,
			"height": 70.88740124695323,
			"seed": 1038914099,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700975447955,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": {
				"elementId": "Ps965qIn6s0_w99_9SBLC",
				"gap": 2.829161402050204,
				"focus": 0.07891939548943307
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					-0.3993960478357508,
					70.88740124695323
				]
			]
		},
		{
			"type": "text",
			"version": 363,
			"versionNonce": 730131778,
			"isDeleted": false,
			"id": "XekcCLy3",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "dashed",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 63.984209465760216,
			"y": 1600.7324899750886,
			"strokeColor": "#e03131",
			"backgroundColor": "transparent",
			"width": 392.3726806640625,
			"height": 22.445325882980562,
			"seed": 1443010995,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "OMwWppUGw5FH6Aep86f-w",
					"type": "arrow"
				}
			],
			"updated": 1700563029727,
			"link": null,
			"locked": false,
			"fontSize": 18.704438235817136,
			"fontFamily": 3,
			"text": "이 virtual NIC을 L2 switch처럼 사용한다.",
			"rawText": "이 virtual NIC을 L2 switch처럼 사용한다.",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "이 virtual NIC을 L2 switch처럼 사용한다.",
			"lineHeight": 1.2,
			"baseline": 18
		},
		{
			"type": "arrow",
			"version": 366,
			"versionNonce": 495275075,
			"isDeleted": false,
			"id": "OMwWppUGw5FH6Aep86f-w",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 50.03413309225448,
			"y": 1585.3431485643373,
			"strokeColor": "#e03131",
			"backgroundColor": "transparent",
			"width": 125.59746347526249,
			"height": 29.105537215705,
			"seed": 701588723,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1700975447952,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "XekcCLy3",
				"focus": 1.1848808267551885,
				"gap": 15.389341410751172
			},
			"endBinding": {
				"elementId": "x0oixotuTO14sWEmTuSYU",
				"gap": 1.0222708447112723,
				"focus": 0.07828957467874403
			},
			"lastCommittedPoint": null,
			"startArrowhead": "arrow",
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					-48.81267373819435,
					29.105537215705
				],
				[
					-125.59746347526249,
					23.967361032737244
				]
			]
		},
		{
			"type": "text",
			"version": 172,
			"versionNonce": 1958343938,
			"isDeleted": false,
			"id": "xVAYoLM3",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -192.96060122771928,
			"y": 1725.8585941506533,
			"strokeColor": "#1971c2",
			"backgroundColor": "transparent",
			"width": 93.75,
			"height": 24,
			"seed": 2139608531,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "EmwoIgJQBLVi5B0KkY3MH",
					"type": "arrow"
				}
			],
			"updated": 1700563029727,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 3,
			"text": "internet",
			"rawText": "internet",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "internet",
			"lineHeight": 1.2,
			"baseline": 20
		},
		{
			"type": "arrow",
			"version": 379,
			"versionNonce": 809028579,
			"isDeleted": false,
			"id": "EmwoIgJQBLVi5B0KkY3MH",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -144.65396094749713,
			"y": 1626.3873892639967,
			"strokeColor": "#1971c2",
			"backgroundColor": "transparent",
			"width": 0.8373896216027958,
			"height": 94.94111818192505,
			"seed": 508343389,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1700975447952,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "x0oixotuTO14sWEmTuSYU",
				"gap": 6.491013771737926,
				"focus": -0.02352957088981262
			},
			"endBinding": {
				"elementId": "xVAYoLM3",
				"gap": 4.530086704731502,
				"focus": 0.009545459876663432
			},
			"lastCommittedPoint": null,
			"startArrowhead": "arrow",
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					-0.8373896216027958,
					94.94111818192505
				]
			]
		},
		{
			"type": "text",
			"version": 530,
			"versionNonce": 695731394,
			"isDeleted": false,
			"id": "SCdUY91x",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 67.6615316359235,
			"y": 1627.517212318235,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 542.9749145507812,
			"height": 24,
			"seed": 171169107,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029727,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 3,
			"text": "NAT(Network Address Translation) 기능 지원(공유기)",
			"rawText": "NAT(Network Address Translation) 기능 지원(공유기)",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "NAT(Network Address Translation) 기능 지원(공유기)",
			"lineHeight": 1.2,
			"baseline": 20
		},
		{
			"type": "text",
			"version": 168,
			"versionNonce": 1300832350,
			"isDeleted": false,
			"id": "3LneMCjA",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -451.535339737565,
			"y": 1847.8075207564973,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 270.634033203125,
			"height": 68.06695278180086,
			"seed": 101424627,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029727,
			"link": null,
			"locked": false,
			"fontSize": 28.36123032575036,
			"fontFamily": 3,
			"text": "도커를 사용하는 이유.\n",
			"rawText": "도커를 사용하는 이유.\n",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "도커를 사용하는 이유.\n",
			"lineHeight": 1.2,
			"baseline": 62
		},
		{
			"type": "rectangle",
			"version": 554,
			"versionNonce": 56499330,
			"isDeleted": false,
			"id": "8FgmT69SqNhaW1EW_jmZv",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -426.2982770353875,
			"y": 2109.864247970467,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 854.4692262229381,
			"height": 1.2251502303088742,
			"seed": 1173564797,
			"groupIds": [
				"8AVsrewYY7cKal7uqRn2L"
			],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [],
			"updated": 1700563029727,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 684,
			"versionNonce": 2122409118,
			"isDeleted": false,
			"id": "PEuGJC-C0kam-OjcffqVX",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -426.2982770353875,
			"y": 2236.915494078824,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 854.4692262229381,
			"height": 1.2251502303088742,
			"seed": 696939997,
			"groupIds": [
				"8AVsrewYY7cKal7uqRn2L"
			],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [],
			"updated": 1700563029727,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 426,
			"versionNonce": 808139842,
			"isDeleted": false,
			"id": "EJol7a69",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -426.2982770353875,
			"y": 2085.107212697863,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 70.3125,
			"height": 48,
			"seed": 1071231549,
			"groupIds": [
				"8AVsrewYY7cKal7uqRn2L"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029727,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 3,
			"text": "User\nKernel",
			"rawText": "User\nKernel",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "User\nKernel",
			"lineHeight": 1.2,
			"baseline": 44
		},
		{
			"type": "text",
			"version": 493,
			"versionNonce": 677847262,
			"isDeleted": false,
			"id": "V6HFMPQK",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -426.2982770353875,
			"y": 2211.5977256748233,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 35.15625,
			"height": 48,
			"seed": 1438802589,
			"groupIds": [
				"8AVsrewYY7cKal7uqRn2L"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029727,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 3,
			"text": "S/W\nH/W",
			"rawText": "S/W\nH/W",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "S/W\nH/W",
			"lineHeight": 1.2,
			"baseline": 44
		},
		{
			"type": "rectangle",
			"version": 359,
			"versionNonce": 1304323074,
			"isDeleted": false,
			"id": "ZwnMPRIsoamwwkW_-z0l_",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -293.35658737550114,
			"y": 2110.193808098823,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 139,
			"height": 73,
			"seed": 536217341,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"type": "text",
					"id": "ogw24fkS"
				}
			],
			"updated": 1700563029727,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 362,
			"versionNonce": 1053512990,
			"isDeleted": false,
			"id": "ogw24fkS",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -259.01283737550114,
			"y": 2134.693808098823,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 70.3125,
			"height": 24,
			"seed": 1089871709,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029727,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 3,
			"text": "TCP/IP",
			"rawText": "TCP/IP",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "ZwnMPRIsoamwwkW_-z0l_",
			"originalText": "TCP/IP",
			"lineHeight": 1.2,
			"baseline": 20
		},
		{
			"type": "rectangle",
			"version": 402,
			"versionNonce": 1712755650,
			"isDeleted": false,
			"id": "78YIq9tRX3RWVsg4_Ypt9",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -293.35658737550114,
			"y": 2203.723331852342,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 139,
			"height": 34,
			"seed": 252980157,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"type": "text",
					"id": "6apG3K9Q"
				}
			],
			"updated": 1700563029727,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 398,
			"versionNonce": 455016798,
			"isDeleted": false,
			"id": "6apG3K9Q",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -259.01283737550114,
			"y": 2208.723331852342,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 70.3125,
			"height": 24,
			"seed": 443657245,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029727,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 3,
			"text": "driver",
			"rawText": "driver",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "78YIq9tRX3RWVsg4_Ypt9",
			"originalText": "driver",
			"lineHeight": 1.2,
			"baseline": 20
		},
		{
			"type": "rectangle",
			"version": 474,
			"versionNonce": 1800588162,
			"isDeleted": false,
			"id": "7TwtMm0i0h-JK3gmtestU",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -293.35658737550114,
			"y": 2238.291407322709,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 139,
			"height": 34,
			"seed": 1929388157,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"type": "text",
					"id": "glIYNbaO"
				}
			],
			"updated": 1700563029727,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 469,
			"versionNonce": 1085482398,
			"isDeleted": false,
			"id": "glIYNbaO",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -241.43471237550114,
			"y": 2243.291407322709,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 35.15625,
			"height": 24,
			"seed": 780208349,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029727,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 3,
			"text": "NIC",
			"rawText": "NIC",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "7TwtMm0i0h-JK3gmtestU",
			"originalText": "NIC",
			"lineHeight": 1.2,
			"baseline": 20
		},
		{
			"type": "rectangle",
			"version": 412,
			"versionNonce": 867306306,
			"isDeleted": false,
			"id": "Jg1ywaa8_AAdhhCGbTMrF",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -293.35658737550114,
			"y": 2002.6414979121532,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 139,
			"height": 73,
			"seed": 780526909,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"type": "text",
					"id": "qTUY1kL4"
				}
			],
			"updated": 1700563029727,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 409,
			"versionNonce": 548979166,
			"isDeleted": false,
			"id": "qTUY1kL4",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -264.87221237550114,
			"y": 2027.1414979121532,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 82.03125,
			"height": 24,
			"seed": 644887965,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029727,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 3,
			"text": "process",
			"rawText": "process",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "Jg1ywaa8_AAdhhCGbTMrF",
			"originalText": "process",
			"lineHeight": 1.2,
			"baseline": 20
		},
		{
			"type": "ellipse",
			"version": 303,
			"versionNonce": 1972589314,
			"isDeleted": false,
			"id": "tA9vxfQ5Ctq56PrdYGGzn",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -240.46635196840805,
			"y": 2077.1120491365887,
			"strokeColor": "#1971c2",
			"backgroundColor": "#ffffff",
			"width": 33.219529185814054,
			"height": 33.219529185814054,
			"seed": 1634826749,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029727,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 308,
			"versionNonce": 1581307422,
			"isDeleted": false,
			"id": "QkWAkxsh",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -239.52450741817233,
			"y": 2084.426707617217,
			"strokeColor": "#1971c2",
			"backgroundColor": "#ffffff",
			"width": 31.3125,
			"height": 16.0439501236954,
			"seed": 1217081949,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029727,
			"link": null,
			"locked": false,
			"fontSize": 13.369958436412833,
			"fontFamily": 3,
			"text": "file",
			"rawText": "file",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "file",
			"lineHeight": 1.2,
			"baseline": 13
		},
		{
			"type": "text",
			"version": 184,
			"versionNonce": 1131782850,
			"isDeleted": false,
			"id": "GDZXWgMC",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -73.36789725732149,
			"y": 1919.221319185583,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 93.75,
			"height": 24,
			"seed": 1805469021,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029727,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 3,
			"text": "Linux #1",
			"rawText": "Linux #1",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Linux #1",
			"lineHeight": 1.2,
			"baseline": 20
		},
		{
			"type": "text",
			"version": 238,
			"versionNonce": 305947230,
			"isDeleted": false,
			"id": "3b6rNCFG",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 74.75284364873198,
			"y": 1919.221319185583,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 93.75,
			"height": 24,
			"seed": 1709609405,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029728,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 3,
			"text": "Linux #2",
			"rawText": "Linux #2",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Linux #2",
			"lineHeight": 1.2,
			"baseline": 20
		},
		{
			"type": "rectangle",
			"version": 598,
			"versionNonce": 133692034,
			"isDeleted": false,
			"id": "wdEKvd41J9hGl7pKbpQ1r",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -66.9057123261477,
			"y": 2030.4344190797956,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 87,
			"height": 46,
			"seed": 1492190845,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029728,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 694,
			"versionNonce": 259810974,
			"isDeleted": false,
			"id": "ji1pf-ewArMceS5whRnkk",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -66.9057123261477,
			"y": 2085.358205746375,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 87,
			"height": 25,
			"seed": 1307921213,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029728,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 835,
			"versionNonce": 31021634,
			"isDeleted": false,
			"id": "4S-XfXhEDGdjFDrDzZfr_",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -66.79846128289125,
			"y": 2110.5330305578354,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 87,
			"height": 25,
			"seed": 1287610365,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029728,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 649,
			"versionNonce": 649192158,
			"isDeleted": false,
			"id": "E7-vQh9lI5Xey4eMVbuEb",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -66.9057123261477,
			"y": 1963.1783849041026,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 87,
			"height": 46,
			"seed": 1511736509,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029728,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 541,
			"versionNonce": 1073267202,
			"isDeleted": false,
			"id": "fc7TEMdgd0o-hIzYom5l0",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -33.792350169369286,
			"y": 2009.9226325765908,
			"strokeColor": "#1971c2",
			"backgroundColor": "#ffffff",
			"width": 20.773275686443146,
			"height": 20.773275686443146,
			"seed": 936704381,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029728,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 221,
			"versionNonce": 1785583390,
			"isDeleted": false,
			"id": "lQ8W768HCR2xv4EDA2hxi",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -92.30528388604392,
			"y": 1951.3277077837697,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 131.38616133871557,
			"height": 196.40085808536514,
			"seed": 1290251933,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029728,
			"link": null,
			"locked": false
		},
		{
			"type": "line",
			"version": 310,
			"versionNonce": 492122562,
			"isDeleted": false,
			"id": "th4EDxprHAuxZOpaVcB3A",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -91.54283339322603,
			"y": 2030.1763837659923,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 130.65003117163326,
			"height": 0.005628918007460015,
			"seed": 479318781,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029728,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					130.65003117163326,
					-0.005628918007460015
				]
			]
		},
		{
			"type": "rectangle",
			"version": 686,
			"versionNonce": 1931559774,
			"isDeleted": false,
			"id": "-i23LHCA1qbfE_o_Shatc",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 81.00273698691194,
			"y": 2030.3950581588601,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 87,
			"height": 46,
			"seed": 512817181,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029728,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 781,
			"versionNonce": 1024305538,
			"isDeleted": false,
			"id": "6FB-pIJVJh2rvOxBDbfGf",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 81.21502857990572,
			"y": 2085.1101513950384,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 87,
			"height": 25,
			"seed": 1413305565,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029728,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 923,
			"versionNonce": 589113246,
			"isDeleted": false,
			"id": "IDudP4AWAtRYcLvP3qkWP",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 81.32227962316216,
			"y": 2110.2849762064993,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 87,
			"height": 25,
			"seed": 1787396509,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029728,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 736,
			"versionNonce": 107030850,
			"isDeleted": false,
			"id": "lLH2nvbkIlswjPn5VsFDP",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 81.21502857990572,
			"y": 1962.9303305527665,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 87,
			"height": 46,
			"seed": 2009169501,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029728,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 628,
			"versionNonce": 1787986910,
			"isDeleted": false,
			"id": "9fgtIrBoiyz2SVTkK9qgM",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 114.32839073668413,
			"y": 2009.6745782252547,
			"strokeColor": "#1971c2",
			"backgroundColor": "#ffffff",
			"width": 20.773275686443146,
			"height": 20.773275686443146,
			"seed": 1865501469,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029728,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 308,
			"versionNonce": 548319490,
			"isDeleted": false,
			"id": "y5g7rAB5oEtIdd0wUiSbZ",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 55.81545702000949,
			"y": 1951.0796534324336,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 131.38616133871557,
			"height": 196.40085808536514,
			"seed": 1062593597,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029728,
			"link": null,
			"locked": false
		},
		{
			"type": "line",
			"version": 396,
			"versionNonce": 194140190,
			"isDeleted": false,
			"id": "n6LTOid8ieSLFU0mYlgIS",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 56.79019910582116,
			"y": 2029.9283294146562,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 130.65003117163326,
			"height": 0.005628918007460015,
			"seed": 988304541,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029728,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					130.65003117163326,
					-0.005628918007460015
				]
			]
		},
		{
			"type": "text",
			"version": 372,
			"versionNonce": 1869955266,
			"isDeleted": false,
			"id": "07FSKEvb",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -376.05308485920455,
			"y": 1932.249200491713,
			"strokeColor": "#e03131",
			"backgroundColor": "transparent",
			"width": 212.08798217773438,
			"height": 31.45303554456793,
			"seed": 1445637107,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029728,
			"link": null,
			"locked": false,
			"fontSize": 26.210862953806608,
			"fontFamily": 3,
			"text": "사용 중인 프로세스",
			"rawText": "사용 중인 프로세스",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "사용 중인 프로세스",
			"lineHeight": 1.2,
			"baseline": 25
		},
		{
			"type": "ellipse",
			"version": 451,
			"versionNonce": 1577952350,
			"isDeleted": false,
			"id": "YyiQz9eVoobMDGrT9c2Zs",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -362.70860605944404,
			"y": 2003.4053576750493,
			"strokeColor": "#e03131",
			"backgroundColor": "#ffffffbb",
			"width": 67,
			"height": 67,
			"seed": 1690929011,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [
				{
					"type": "text",
					"id": "qLrh0dQB"
				}
			],
			"updated": 1700563029728,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 365,
			"versionNonce": 240375938,
			"isDeleted": false,
			"id": "qLrh0dQB",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -335.2560582291934,
			"y": 2024.7172805053,
			"strokeColor": "#e03131",
			"backgroundColor": "transparent",
			"width": 11.71875,
			"height": 24,
			"seed": 1871507709,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029728,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 3,
			"text": "1",
			"rawText": "1",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "YyiQz9eVoobMDGrT9c2Zs",
			"originalText": "1",
			"lineHeight": 1.2,
			"baseline": 20
		},
		{
			"type": "ellipse",
			"version": 369,
			"versionNonce": 332753054,
			"isDeleted": false,
			"id": "WYd14eyU0GOBa9NJ0YSG7",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -362.70860605944404,
			"y": 2142.67943716674,
			"strokeColor": "#e03131",
			"backgroundColor": "#ffffffbb",
			"width": 67,
			"height": 67,
			"seed": 1778988403,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [
				{
					"type": "text",
					"id": "Nbvm7uNb"
				}
			],
			"updated": 1700563029728,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 286,
			"versionNonce": 1292466242,
			"isDeleted": false,
			"id": "Nbvm7uNb",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -335.2560582291934,
			"y": 2163.991359996991,
			"strokeColor": "#e03131",
			"backgroundColor": "transparent",
			"width": 11.71875,
			"height": 24,
			"seed": 13111059,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029728,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 3,
			"text": "2",
			"rawText": "2",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "WYd14eyU0GOBa9NJ0YSG7",
			"originalText": "2",
			"lineHeight": 1.2,
			"baseline": 20
		},
		{
			"type": "ellipse",
			"version": 304,
			"versionNonce": 2090509534,
			"isDeleted": false,
			"id": "f39KqjulOliJaP1fv2_vu",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -110.41803859931571,
			"y": 1953.6715543130174,
			"strokeColor": "#e03131",
			"backgroundColor": "#ffffffbb",
			"width": 67,
			"height": 67,
			"seed": 1899385459,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [
				{
					"type": "text",
					"id": "HZNEkPXT"
				}
			],
			"updated": 1700563029728,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 223,
			"versionNonce": 729096194,
			"isDeleted": false,
			"id": "HZNEkPXT",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -82.96549076906506,
			"y": 1974.9834771432681,
			"strokeColor": "#e03131",
			"backgroundColor": "transparent",
			"width": 11.71875,
			"height": 24,
			"seed": 1045007379,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029728,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 3,
			"text": "3",
			"rawText": "3",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "f39KqjulOliJaP1fv2_vu",
			"originalText": "3",
			"lineHeight": 1.2,
			"baseline": 20
		},
		{
			"type": "ellipse",
			"version": 249,
			"versionNonce": 1240357150,
			"isDeleted": false,
			"id": "pubSFhpGMFvL8Vwx5marz",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -110.41803859931571,
			"y": 2037.6652628053916,
			"strokeColor": "#e03131",
			"backgroundColor": "#ffffffbb",
			"width": 67,
			"height": 67,
			"seed": 1597173597,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [
				{
					"type": "text",
					"id": "aLmHV2dH"
				}
			],
			"updated": 1700563029728,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 168,
			"versionNonce": 1435881410,
			"isDeleted": false,
			"id": "aLmHV2dH",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -82.96549076906506,
			"y": 2058.9771856356424,
			"strokeColor": "#e03131",
			"backgroundColor": "transparent",
			"width": 11.71875,
			"height": 24,
			"seed": 1832319933,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029728,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 3,
			"text": "4",
			"rawText": "4",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "pubSFhpGMFvL8Vwx5marz",
			"originalText": "4",
			"lineHeight": 1.2,
			"baseline": 20
		},
		{
			"type": "ellipse",
			"version": 296,
			"versionNonce": 1396802910,
			"isDeleted": false,
			"id": "FreclInDkCMzq8ZDM6osD",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -110.20934516891504,
			"y": 2121.6589712977657,
			"strokeColor": "#e03131",
			"backgroundColor": "#ffffffbb",
			"width": 67,
			"height": 67,
			"seed": 180822099,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [
				{
					"type": "text",
					"id": "kyLr6Kfj"
				}
			],
			"updated": 1700563029728,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 215,
			"versionNonce": 529172354,
			"isDeleted": false,
			"id": "kyLr6Kfj",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -82.75679733866438,
			"y": 2142.9708941280164,
			"strokeColor": "#e03131",
			"backgroundColor": "transparent",
			"width": 11.71875,
			"height": 24,
			"seed": 1816501747,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029728,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 3,
			"text": "5",
			"rawText": "5",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "FreclInDkCMzq8ZDM6osD",
			"originalText": "5",
			"lineHeight": 1.2,
			"baseline": 20
		},
		{
			"type": "ellipse",
			"version": 314,
			"versionNonce": 1508190622,
			"isDeleted": false,
			"id": "fwZ5bZvte1gc5EDn4lGKs",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 46.57519258216922,
			"y": 1952.6604706243522,
			"strokeColor": "#e03131",
			"backgroundColor": "#ffffffbb",
			"width": 67,
			"height": 67,
			"seed": 1251444787,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [
				{
					"type": "text",
					"id": "UlLBeCjz"
				}
			],
			"updated": 1700563029728,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 235,
			"versionNonce": 26363714,
			"isDeleted": false,
			"id": "UlLBeCjz",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 74.02774041241989,
			"y": 1973.972393454603,
			"strokeColor": "#e03131",
			"backgroundColor": "transparent",
			"width": 11.71875,
			"height": 24,
			"seed": 1232996819,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029728,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 3,
			"text": "6",
			"rawText": "6",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "fwZ5bZvte1gc5EDn4lGKs",
			"originalText": "6",
			"lineHeight": 1.2,
			"baseline": 20
		},
		{
			"type": "ellipse",
			"version": 290,
			"versionNonce": 1292518878,
			"isDeleted": false,
			"id": "LfdgQ2ckBlFB-vur9_rH-",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 46.57519258216922,
			"y": 2036.6541791167265,
			"strokeColor": "#e03131",
			"backgroundColor": "#ffffffbb",
			"width": 67,
			"height": 67,
			"seed": 1783864733,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [
				{
					"type": "text",
					"id": "6yrAxyfw"
				}
			],
			"updated": 1700563029728,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 211,
			"versionNonce": 336334594,
			"isDeleted": false,
			"id": "6yrAxyfw",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 74.02774041241989,
			"y": 2057.9661019469772,
			"strokeColor": "#e03131",
			"backgroundColor": "transparent",
			"width": 11.71875,
			"height": 24,
			"seed": 614982141,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029728,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 3,
			"text": "7",
			"rawText": "7",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "LfdgQ2ckBlFB-vur9_rH-",
			"originalText": "7",
			"lineHeight": 1.2,
			"baseline": 20
		},
		{
			"type": "ellipse",
			"version": 302,
			"versionNonce": 230808094,
			"isDeleted": false,
			"id": "hBhL0nk-WXJ9fFm1Zf1dS",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 46.57519258216922,
			"y": 2120.6478876091005,
			"strokeColor": "#e03131",
			"backgroundColor": "#ffffffbb",
			"width": 67,
			"height": 67,
			"seed": 155764435,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [
				{
					"type": "text",
					"id": "thEL5kk8"
				}
			],
			"updated": 1700563029728,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 223,
			"versionNonce": 192339650,
			"isDeleted": false,
			"id": "thEL5kk8",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 74.02774041241989,
			"y": 2141.9598104393513,
			"strokeColor": "#e03131",
			"backgroundColor": "transparent",
			"width": 11.71875,
			"height": 24,
			"seed": 684618867,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029728,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 3,
			"text": "8",
			"rawText": "8",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "hBhL0nk-WXJ9fFm1Zf1dS",
			"originalText": "8",
			"lineHeight": 1.2,
			"baseline": 20
		},
		{
			"type": "text",
			"version": 160,
			"versionNonce": 855434846,
			"isDeleted": false,
			"id": "oHlAJ0BV",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -344.2093459101397,
			"y": 2322.3152127235016,
			"strokeColor": "#e03131",
			"backgroundColor": "#ffffffbb",
			"width": 416.8685302734375,
			"height": 24,
			"seed": 2137550579,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029728,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 3,
			"text": "8개나 되는 프로세스 중, 요놈들은 꼭 필요한가?",
			"rawText": "8개나 되는 프로세스 중, 요놈들은 꼭 필요한가?",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "8개나 되는 프로세스 중, 요놈들은 꼭 필요한가?",
			"lineHeight": 1.2,
			"baseline": 20
		},
		{
			"type": "rectangle",
			"version": 187,
			"versionNonce": 879867522,
			"isDeleted": false,
			"id": "69txMRJZQNOhNXlh5YT2z",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -119.19105182452427,
			"y": 2029.4751519202669,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffffff99",
			"width": 248.60065172088923,
			"height": 168.3796167073965,
			"seed": 1007617363,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [],
			"updated": 1700563029728,
			"link": null,
			"locked": false
		},
		{
			"type": "line",
			"version": 159,
			"versionNonce": 1301047966,
			"isDeleted": false,
			"id": "SSup2zlsdeXU6YUNQyvwL",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -18.795119151437348,
			"y": 2198.506036057017,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffffff99",
			"width": 78.24229649657764,
			"height": 124.21030334878105,
			"seed": 288458077,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1700563029728,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-78.24229649657764,
					124.21030334878105
				]
			]
		},
		{
			"type": "text",
			"version": 249,
			"versionNonce": 1874564674,
			"isDeleted": false,
			"id": "IIcthEKq",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -444.96878052977235,
			"y": 3027.076458408657,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffffff99",
			"width": 155.37493896484375,
			"height": 48,
			"seed": 516477139,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029728,
			"link": "[[쿠버네티스]]",
			"locked": false,
			"fontSize": 20,
			"fontFamily": 3,
			"text": "📍[[쿠버네티스]]\n",
			"rawText": "[[쿠버네티스|쿠버네티스]]\n",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "📍[[쿠버네티스]]\n",
			"lineHeight": 1.2,
			"baseline": 44
		},
		{
			"type": "image",
			"version": 196,
			"versionNonce": 740386526,
			"isDeleted": false,
			"id": "2gX7NPxq",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -478.3265287251245,
			"y": 2538.450963908209,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 1240.9032193958674,
			"height": 459.13419117647095,
			"seed": 19720,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029728,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "c6c86de84d2fa95cc04b57a4c2191bbbbc7dd6c2",
			"scale": [
				1,
				1
			]
		},
		{
			"type": "text",
			"version": 102,
			"versionNonce": 775126530,
			"isDeleted": false,
			"id": "tDVObzfZ",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -445.70704343100715,
			"y": 2992.544713908208,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffffff99",
			"width": 620.5374755859375,
			"height": 24,
			"seed": 1374991229,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029728,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 3,
			"text": "출처: https://kubernetes.io/ko/docs/concepts/overview/",
			"rawText": "출처: https://kubernetes.io/ko/docs/concepts/overview/",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "출처: https://kubernetes.io/ko/docs/concepts/overview/",
			"lineHeight": 1.2,
			"baseline": 20
		},
		{
			"type": "rectangle",
			"version": 628,
			"versionNonce": 525130526,
			"isDeleted": false,
			"id": "WB1clmcMuLd78bHI7sjWN",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -442.87272271894676,
			"y": 3257.35023124351,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 1181.389348196015,
			"height": 1.6938929894815955,
			"seed": 1283338269,
			"groupIds": [
				"tp7cUzSUkea6U5b3P17TX"
			],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [],
			"updated": 1700563029728,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 758,
			"versionNonce": 1826123202,
			"isDeleted": false,
			"id": "lSPr9wQR_Ef-M_tZPD8AV",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -442.87272271894676,
			"y": 3433.0113132592132,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 1181.389348196015,
			"height": 1.6938929894815955,
			"seed": 953951357,
			"groupIds": [
				"tp7cUzSUkea6U5b3P17TX"
			],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [],
			"updated": 1700563029728,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 500,
			"versionNonce": 1031784286,
			"isDeleted": false,
			"id": "tehsIeFQ",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -442.87272271894676,
			"y": 3223.1211485962,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 97.20703125,
			"height": 66.36481101147751,
			"seed": 1648135389,
			"groupIds": [
				"tp7cUzSUkea6U5b3P17TX"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029728,
			"link": null,
			"locked": false,
			"fontSize": 27.65200458811563,
			"fontFamily": 3,
			"text": "User\nKernel",
			"rawText": "User\nKernel",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "User\nKernel",
			"lineHeight": 1.2,
			"baseline": 60
		},
		{
			"type": "text",
			"version": 567,
			"versionNonce": 818505090,
			"isDeleted": false,
			"id": "QAStuCMg",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -442.87272271894676,
			"y": 3398.0069608558006,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 48.603515625,
			"height": 66.36481101147751,
			"seed": 1748035901,
			"groupIds": [
				"tp7cUzSUkea6U5b3P17TX"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029728,
			"link": null,
			"locked": false,
			"fontSize": 27.65200458811563,
			"fontFamily": 3,
			"text": "S/W\nH/W",
			"rawText": "S/W\nH/W",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "S/W\nH/W",
			"lineHeight": 1.2,
			"baseline": 60
		},
		{
			"type": "text",
			"version": 86,
			"versionNonce": 655043486,
			"isDeleted": false,
			"id": "i8MSAe21",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -320.6289184310068,
			"y": 3521.24416243762,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffffff99",
			"width": 105.46875,
			"height": 24,
			"seed": 1152327517,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029728,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 3,
			"text": "OS: Linux",
			"rawText": "OS: Linux",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "OS: Linux",
			"lineHeight": 1.2,
			"baseline": 20
		},
		{
			"type": "line",
			"version": 2539,
			"versionNonce": 54879554,
			"isDeleted": false,
			"id": "x1y6WTFtb3B7-07X1il_V",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2459.372642030014,
			"y": -98.4095427835936,
			"strokeColor": "#0091e2",
			"backgroundColor": "#0091e2",
			"width": 56.62135476067269,
			"height": 27.78137540135306,
			"seed": 756069897,
			"groupIds": [
				"RMWuTdtNmWNG5snxZH6q6"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1700563029728,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					26.49928798736996,
					-0.5555399791810629
				],
				[
					32.86897029257218,
					-1.351746926303818
				],
				[
					31.54797965057393,
					-6.47281952059744
				],
				[
					33.64708101980081,
					-11.340553540806383
				],
				[
					36.88620050527203,
					-6.798543885447785
				],
				[
					36.45191491873459,
					-3.1432192393850187
				],
				[
					41.67251763363534,
					-6.7171136294920615
				],
				[
					45.75309251293886,
					-5.2242237812582175
				],
				[
					43.32826283037451,
					-1.9398610124836608
				],
				[
					37.99003529362133,
					0.5844902862542796
				],
				[
					24.0563885094017,
					14.925301714362618
				],
				[
					0.1701084154921375,
					16.440821860546677
				],
				[
					-10.868262247733824,
					1.1146897259718145
				],
				[
					-3.582944626162501,
					-0.5971552103421658
				],
				[
					-0.28719357028327863,
					-0.019545320337599037
				]
			]
		},
		{
			"type": "rectangle",
			"version": 1444,
			"versionNonce": 1243613150,
			"isDeleted": false,
			"id": "6TycDLbhGIB6BkZ14wYWC",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2453.0876833429843,
			"y": -106.22178075635875,
			"strokeColor": "#0091e2",
			"backgroundColor": "#0091e2",
			"width": 5.566352494330056,
			"height": 5.566352494330056,
			"seed": 1467944169,
			"groupIds": [
				"RMWuTdtNmWNG5snxZH6q6"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029728,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 1499,
			"versionNonce": 1839951106,
			"isDeleted": false,
			"id": "yRfIka7vSiZMcbLhg1-Jz",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2460.045622014452,
			"y": -106.47690106082783,
			"strokeColor": "#0091e2",
			"backgroundColor": "#0091e2",
			"width": 5.566352494330056,
			"height": 5.566352494330056,
			"seed": 331319241,
			"groupIds": [
				"RMWuTdtNmWNG5snxZH6q6"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029728,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 1519,
			"versionNonce": 651123742,
			"isDeleted": false,
			"id": "BopARhgRSfpva2CEaKOZt",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2467.3282585474494,
			"y": -106.36094754913543,
			"strokeColor": "#0091e2",
			"backgroundColor": "#0091e2",
			"width": 5.566352494330056,
			"height": 5.566352494330056,
			"seed": 736994985,
			"groupIds": [
				"RMWuTdtNmWNG5snxZH6q6"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029728,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 1540,
			"versionNonce": 1970961602,
			"isDeleted": false,
			"id": "MUk4dJegwFkxffKX2odPl",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2474.5877012638016,
			"y": -106.708831441537,
			"strokeColor": "#0091e2",
			"backgroundColor": "#0091e2",
			"width": 5.566352494330056,
			"height": 5.566352494330056,
			"seed": 448063881,
			"groupIds": [
				"RMWuTdtNmWNG5snxZH6q6"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029728,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 1582,
			"versionNonce": 319432798,
			"isDeleted": false,
			"id": "uiJog8FNBT3KB5doC-GFF",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2481.47605459244,
			"y": -106.61606396072116,
			"strokeColor": "#0091e2",
			"backgroundColor": "#0091e2",
			"width": 5.566352494330056,
			"height": 5.566352494330056,
			"seed": 2035339369,
			"groupIds": [
				"RMWuTdtNmWNG5snxZH6q6"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029728,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 1486,
			"versionNonce": 407999618,
			"isDeleted": false,
			"id": "v8192IljrMeyXABc2FxIc",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2459.848472626499,
			"y": -113.22609148957773,
			"strokeColor": "#0091e2",
			"backgroundColor": "#0091e2",
			"width": 5.566352494330056,
			"height": 5.566352494330056,
			"seed": 764205897,
			"groupIds": [
				"RMWuTdtNmWNG5snxZH6q6"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029728,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 1510,
			"versionNonce": 2124508318,
			"isDeleted": false,
			"id": "uqF4Lg0MhHMzYQnZSQSKy",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2467.154306869033,
			"y": -113.13332011587605,
			"strokeColor": "#0091e2",
			"backgroundColor": "#0091e2",
			"width": 5.566352494330056,
			"height": 5.566352494330056,
			"seed": 1472498217,
			"groupIds": [
				"RMWuTdtNmWNG5snxZH6q6"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029728,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 1534,
			"versionNonce": 1206891586,
			"isDeleted": false,
			"id": "NLg4L7ez-7xUCb2ufIitK",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2474.5529124852715,
			"y": -113.13332790164387,
			"strokeColor": "#0091e2",
			"backgroundColor": "#0091e2",
			"width": 5.566352494330056,
			"height": 5.566352494330056,
			"seed": 14900489,
			"groupIds": [
				"RMWuTdtNmWNG5snxZH6q6"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029728,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 1553,
			"versionNonce": 927344862,
			"isDeleted": false,
			"id": "9-HZw1sz7qIuxXu-wSsZY",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2474.3093754640236,
			"y": -120.23042168722796,
			"strokeColor": "#0091e2",
			"backgroundColor": "#0091e2",
			"width": 5.566352494330056,
			"height": 5.566352494330056,
			"seed": 140825577,
			"groupIds": [
				"RMWuTdtNmWNG5snxZH6q6"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029728,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 106,
			"versionNonce": 1714674690,
			"isDeleted": false,
			"id": "B6rz698sncOsPUlTjK4Vo",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2396.366911219101,
			"y": -151.8260521914786,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 164.7718652749404,
			"height": 103.77037411349465,
			"seed": 777529735,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"id": "eWU6nwSpXBYruJ7FZ5nJS",
					"type": "arrow"
				},
				{
					"id": "pJkTtNK1k1c2Z8Ynzh5pK",
					"type": "arrow"
				},
				{
					"id": "HhA7U0xRTPUBRrwc9Aqfo",
					"type": "arrow"
				}
			],
			"updated": 1700563029728,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 221,
			"versionNonce": 747199774,
			"isDeleted": false,
			"id": "VGoIzV7u",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2411.123603146176,
			"y": -140.49825932165052,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 134.26492309570312,
			"height": 16.405092478761514,
			"seed": 1043186089,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029728,
			"link": null,
			"locked": false,
			"fontSize": 13.670910398967928,
			"fontFamily": 3,
			"text": "컨테이너 이미지 저장소",
			"rawText": "컨테이너 이미지 저장소",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "컨테이너 이미지 저장소",
			"lineHeight": 1.2,
			"baseline": 13
		},
		{
			"type": "line",
			"version": 2628,
			"versionNonce": 1092422594,
			"isDeleted": false,
			"id": "ENJkVwj8WQuQloIZRI927",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2307.956741973613,
			"y": 96.3175034239428,
			"strokeColor": "#0091e2",
			"backgroundColor": "#0091e2",
			"width": 56.62135476067269,
			"height": 27.78137540135306,
			"seed": 2085276135,
			"groupIds": [
				"UzLZEkRtqme_aqWNTe4r0"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1700563029728,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					26.49928798736996,
					-0.5555399791810629
				],
				[
					32.86897029257218,
					-1.351746926303818
				],
				[
					31.54797965057393,
					-6.47281952059744
				],
				[
					33.64708101980081,
					-11.340553540806383
				],
				[
					36.88620050527203,
					-6.798543885447785
				],
				[
					36.45191491873459,
					-3.1432192393850187
				],
				[
					41.67251763363534,
					-6.7171136294920615
				],
				[
					45.75309251293886,
					-5.2242237812582175
				],
				[
					43.32826283037451,
					-1.9398610124836608
				],
				[
					37.99003529362133,
					0.5844902862542796
				],
				[
					24.0563885094017,
					14.925301714362618
				],
				[
					0.1701084154921375,
					16.440821860546677
				],
				[
					-10.868262247733824,
					1.1146897259718145
				],
				[
					-3.582944626162501,
					-0.5971552103421658
				],
				[
					-0.28719357028327863,
					-0.019545320337599037
				]
			]
		},
		{
			"type": "rectangle",
			"version": 1533,
			"versionNonce": 870058334,
			"isDeleted": false,
			"id": "U1_HkC39KcQC78rkw2j6X",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2301.6717832865834,
			"y": 88.50526545117764,
			"strokeColor": "#0091e2",
			"backgroundColor": "#0091e2",
			"width": 5.566352494330056,
			"height": 5.566352494330056,
			"seed": 1816589575,
			"groupIds": [
				"UzLZEkRtqme_aqWNTe4r0"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029728,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 1588,
			"versionNonce": 248136578,
			"isDeleted": false,
			"id": "tHW4bS6ALHrzqWNhusVMY",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2308.629721958051,
			"y": 88.25014514670856,
			"strokeColor": "#0091e2",
			"backgroundColor": "#0091e2",
			"width": 5.566352494330056,
			"height": 5.566352494330056,
			"seed": 1573960743,
			"groupIds": [
				"UzLZEkRtqme_aqWNTe4r0"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029728,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 1608,
			"versionNonce": 1284451742,
			"isDeleted": false,
			"id": "sWzOxHkVBNHowgZ1AeRKS",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2315.9123584910485,
			"y": 88.36609865840096,
			"strokeColor": "#0091e2",
			"backgroundColor": "#0091e2",
			"width": 5.566352494330056,
			"height": 5.566352494330056,
			"seed": 81043271,
			"groupIds": [
				"UzLZEkRtqme_aqWNTe4r0"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029728,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 1629,
			"versionNonce": 1769636674,
			"isDeleted": false,
			"id": "d_uAZZBTYycHdbtufs-3o",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2323.1718012074007,
			"y": 88.01821476599939,
			"strokeColor": "#0091e2",
			"backgroundColor": "#0091e2",
			"width": 5.566352494330056,
			"height": 5.566352494330056,
			"seed": 1672420967,
			"groupIds": [
				"UzLZEkRtqme_aqWNTe4r0"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029728,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 1671,
			"versionNonce": 1674824158,
			"isDeleted": false,
			"id": "Ax21GTrLQfxQmhMBZZ4IR",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2330.0601545360396,
			"y": 88.11098224681523,
			"strokeColor": "#0091e2",
			"backgroundColor": "#0091e2",
			"width": 5.566352494330056,
			"height": 5.566352494330056,
			"seed": 2100083079,
			"groupIds": [
				"UzLZEkRtqme_aqWNTe4r0"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029728,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 1575,
			"versionNonce": 1267518210,
			"isDeleted": false,
			"id": "BweVtoczfM0txr9KMMEPL",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2308.4325725700983,
			"y": 81.50095471795866,
			"strokeColor": "#0091e2",
			"backgroundColor": "#0091e2",
			"width": 5.566352494330056,
			"height": 5.566352494330056,
			"seed": 1183445159,
			"groupIds": [
				"UzLZEkRtqme_aqWNTe4r0"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029728,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 1599,
			"versionNonce": 414899742,
			"isDeleted": false,
			"id": "fqTHZo7gr_BKbfmNlTIDo",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2315.738406812632,
			"y": 81.59372609166034,
			"strokeColor": "#0091e2",
			"backgroundColor": "#0091e2",
			"width": 5.566352494330056,
			"height": 5.566352494330056,
			"seed": 1500726215,
			"groupIds": [
				"UzLZEkRtqme_aqWNTe4r0"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029728,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 1623,
			"versionNonce": 192944834,
			"isDeleted": false,
			"id": "SEbc5zDt-k2kpr5-9QnBK",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2323.1370124288705,
			"y": 81.59371830589252,
			"strokeColor": "#0091e2",
			"backgroundColor": "#0091e2",
			"width": 5.566352494330056,
			"height": 5.566352494330056,
			"seed": 1711616743,
			"groupIds": [
				"UzLZEkRtqme_aqWNTe4r0"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029729,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 1642,
			"versionNonce": 3500638,
			"isDeleted": false,
			"id": "MHAoKFiUA2X75oJPq7CWy",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2322.8934754076226,
			"y": 74.49662452030843,
			"strokeColor": "#0091e2",
			"backgroundColor": "#0091e2",
			"width": 5.566352494330056,
			"height": 5.566352494330056,
			"seed": 1691106823,
			"groupIds": [
				"UzLZEkRtqme_aqWNTe4r0"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029729,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 82,
			"versionNonce": 1475572354,
			"isDeleted": false,
			"id": "uFgOPfOT",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2282.282972948107,
			"y": 37.807850028418045,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 80.918701171875,
			"height": 24,
			"seed": 1746049705,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029729,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 3,
			"text": "개발 환경",
			"rawText": "개발 환경",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "개발 환경",
			"lineHeight": 1.2,
			"baseline": 20
		},
		{
			"type": "rectangle",
			"version": 219,
			"versionNonce": 1762946718,
			"isDeleted": false,
			"id": "XooU3nfaAi13KPy-Zlgz4",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2586.1879913523057,
			"y": -13.722062958624122,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 78,
			"height": 99,
			"seed": 665491785,
			"groupIds": [
				"cjcvIptBcxq1OcqRfgYEu"
			],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"type": "text",
					"id": "9b6caVYq"
				},
				{
					"id": "eWU6nwSpXBYruJ7FZ5nJS",
					"type": "arrow"
				},
				{
					"id": "4R7e3vGvMDJKts_sRHLuZ",
					"type": "arrow"
				}
			],
			"updated": 1700563029729,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 185,
			"versionNonce": 866505282,
			"isDeleted": false,
			"id": "9b6caVYq",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2607.888003559337,
			"y": -0.22206295862412162,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 34.5999755859375,
			"height": 72,
			"seed": 1746711111,
			"groupIds": [
				"cjcvIptBcxq1OcqRfgYEu"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029729,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 3,
			"text": "서버\n\n",
			"rawText": "서버\n\n",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "XooU3nfaAi13KPy-Zlgz4",
			"originalText": "서버\n\n",
			"lineHeight": 1.2,
			"baseline": 68
		},
		{
			"type": "line",
			"version": 2869,
			"versionNonce": 537455326,
			"isDeleted": false,
			"id": "lHlFQnAVhpmlD2cWsHBXR",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2607.7503233573593,
			"y": 54.70054248622887,
			"strokeColor": "#0091e2",
			"backgroundColor": "#0091e2",
			"width": 56.62135476067269,
			"height": 27.78137540135306,
			"seed": 627429033,
			"groupIds": [
				"5SPquNTzbdtecufp-4Ny4",
				"cjcvIptBcxq1OcqRfgYEu"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1700563029729,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					26.49928798736996,
					-0.5555399791810629
				],
				[
					32.86897029257218,
					-1.351746926303818
				],
				[
					31.54797965057393,
					-6.47281952059744
				],
				[
					33.64708101980081,
					-11.340553540806383
				],
				[
					36.88620050527203,
					-6.798543885447785
				],
				[
					36.45191491873459,
					-3.1432192393850187
				],
				[
					41.67251763363534,
					-6.7171136294920615
				],
				[
					45.75309251293886,
					-5.2242237812582175
				],
				[
					43.32826283037451,
					-1.9398610124836608
				],
				[
					37.99003529362133,
					0.5844902862542796
				],
				[
					24.0563885094017,
					14.925301714362618
				],
				[
					0.1701084154921375,
					16.440821860546677
				],
				[
					-10.868262247733824,
					1.1146897259718145
				],
				[
					-3.582944626162501,
					-0.5971552103421658
				],
				[
					-0.28719357028327863,
					-0.019545320337599037
				]
			]
		},
		{
			"type": "rectangle",
			"version": 1774,
			"versionNonce": 1903573506,
			"isDeleted": false,
			"id": "Vv1re6QtaRdDd1jm_mdNJ",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2601.4653646703296,
			"y": 46.88830451346371,
			"strokeColor": "#0091e2",
			"backgroundColor": "#0091e2",
			"width": 5.566352494330056,
			"height": 5.566352494330056,
			"seed": 48763273,
			"groupIds": [
				"5SPquNTzbdtecufp-4Ny4",
				"cjcvIptBcxq1OcqRfgYEu"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029729,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 1829,
			"versionNonce": 866377502,
			"isDeleted": false,
			"id": "PI--eMmZbERyJYRqJgC_c",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2608.4233033417972,
			"y": 46.633184208994635,
			"strokeColor": "#0091e2",
			"backgroundColor": "#0091e2",
			"width": 5.566352494330056,
			"height": 5.566352494330056,
			"seed": 1088354409,
			"groupIds": [
				"5SPquNTzbdtecufp-4Ny4",
				"cjcvIptBcxq1OcqRfgYEu"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029729,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 1849,
			"versionNonce": 811837890,
			"isDeleted": false,
			"id": "e18xDran7dR3PJsSFk3FA",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2615.7059398747947,
			"y": 46.74913772068703,
			"strokeColor": "#0091e2",
			"backgroundColor": "#0091e2",
			"width": 5.566352494330056,
			"height": 5.566352494330056,
			"seed": 823526217,
			"groupIds": [
				"5SPquNTzbdtecufp-4Ny4",
				"cjcvIptBcxq1OcqRfgYEu"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029729,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 1870,
			"versionNonce": 945179486,
			"isDeleted": false,
			"id": "ZXXOr40u4xAw4Sbt9xMpv",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2622.965382591147,
			"y": 46.40125382828546,
			"strokeColor": "#0091e2",
			"backgroundColor": "#0091e2",
			"width": 5.566352494330056,
			"height": 5.566352494330056,
			"seed": 1609085481,
			"groupIds": [
				"5SPquNTzbdtecufp-4Ny4",
				"cjcvIptBcxq1OcqRfgYEu"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029729,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 1912,
			"versionNonce": 1468866946,
			"isDeleted": false,
			"id": "k1ZWSdX_KwCWGupQwg602",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2629.853735919786,
			"y": 46.4940213091013,
			"strokeColor": "#0091e2",
			"backgroundColor": "#0091e2",
			"width": 5.566352494330056,
			"height": 5.566352494330056,
			"seed": 1111655689,
			"groupIds": [
				"5SPquNTzbdtecufp-4Ny4",
				"cjcvIptBcxq1OcqRfgYEu"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029729,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 1816,
			"versionNonce": 208744350,
			"isDeleted": false,
			"id": "bURRgDU79IAMy3ZB_9-Jh",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2608.2261539538445,
			"y": 39.88399378024474,
			"strokeColor": "#0091e2",
			"backgroundColor": "#0091e2",
			"width": 5.566352494330056,
			"height": 5.566352494330056,
			"seed": 597621737,
			"groupIds": [
				"5SPquNTzbdtecufp-4Ny4",
				"cjcvIptBcxq1OcqRfgYEu"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029729,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 1840,
			"versionNonce": 305242434,
			"isDeleted": false,
			"id": "EpKnrEqysAmZQaPLHcflV",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2615.5319881963783,
			"y": 39.97676515394642,
			"strokeColor": "#0091e2",
			"backgroundColor": "#0091e2",
			"width": 5.566352494330056,
			"height": 5.566352494330056,
			"seed": 1409914569,
			"groupIds": [
				"5SPquNTzbdtecufp-4Ny4",
				"cjcvIptBcxq1OcqRfgYEu"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029729,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 1864,
			"versionNonce": 472222686,
			"isDeleted": false,
			"id": "30u7Ol-CuwahjOpZzDess",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2622.9305938126167,
			"y": 39.976757368178596,
			"strokeColor": "#0091e2",
			"backgroundColor": "#0091e2",
			"width": 5.566352494330056,
			"height": 5.566352494330056,
			"seed": 371053993,
			"groupIds": [
				"5SPquNTzbdtecufp-4Ny4",
				"cjcvIptBcxq1OcqRfgYEu"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029729,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 1883,
			"versionNonce": 1269836034,
			"isDeleted": false,
			"id": "tAf1We7r3rlZQ0x9k3U1B",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2622.687056791369,
			"y": 32.8796635825945,
			"strokeColor": "#0091e2",
			"backgroundColor": "#0091e2",
			"width": 5.566352494330056,
			"height": 5.566352494330056,
			"seed": 1292318857,
			"groupIds": [
				"5SPquNTzbdtecufp-4Ny4",
				"cjcvIptBcxq1OcqRfgYEu"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029729,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 300,
			"versionNonce": 629432350,
			"isDeleted": false,
			"id": "3EkOZNHTojwr7UPD2829O",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2586.1879913523057,
			"y": 115.33831706110323,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 78,
			"height": 99,
			"seed": 2144976457,
			"groupIds": [
				"cjcvIptBcxq1OcqRfgYEu"
			],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"type": "text",
					"id": "xxr8gurs"
				},
				{
					"id": "pJkTtNK1k1c2Z8Ynzh5pK",
					"type": "arrow"
				},
				{
					"id": "VdW1hKzXFvvpuy4eOJcF5",
					"type": "arrow"
				}
			],
			"updated": 1700563029729,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 266,
			"versionNonce": 730314946,
			"isDeleted": false,
			"id": "xxr8gurs",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2607.888003559337,
			"y": 128.83831706110323,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 34.5999755859375,
			"height": 72,
			"seed": 880610601,
			"groupIds": [
				"cjcvIptBcxq1OcqRfgYEu"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029729,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 3,
			"text": "서버\n\n",
			"rawText": "서버\n\n",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "3EkOZNHTojwr7UPD2829O",
			"originalText": "서버\n\n",
			"lineHeight": 1.2,
			"baseline": 68
		},
		{
			"type": "line",
			"version": 2950,
			"versionNonce": 2088676446,
			"isDeleted": false,
			"id": "qRYl6BRSsNgO4ZCJC4IQ1",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2607.7503233573593,
			"y": 183.76092250595622,
			"strokeColor": "#0091e2",
			"backgroundColor": "#0091e2",
			"width": 56.62135476067269,
			"height": 27.78137540135306,
			"seed": 1502838793,
			"groupIds": [
				"OiCzvWt7tMx1qqWgWWHBO",
				"cjcvIptBcxq1OcqRfgYEu"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1700563029729,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					26.49928798736996,
					-0.5555399791810629
				],
				[
					32.86897029257218,
					-1.351746926303818
				],
				[
					31.54797965057393,
					-6.47281952059744
				],
				[
					33.64708101980081,
					-11.340553540806383
				],
				[
					36.88620050527203,
					-6.798543885447785
				],
				[
					36.45191491873459,
					-3.1432192393850187
				],
				[
					41.67251763363534,
					-6.7171136294920615
				],
				[
					45.75309251293886,
					-5.2242237812582175
				],
				[
					43.32826283037451,
					-1.9398610124836608
				],
				[
					37.99003529362133,
					0.5844902862542796
				],
				[
					24.0563885094017,
					14.925301714362618
				],
				[
					0.1701084154921375,
					16.440821860546677
				],
				[
					-10.868262247733824,
					1.1146897259718145
				],
				[
					-3.582944626162501,
					-0.5971552103421658
				],
				[
					-0.28719357028327863,
					-0.019545320337599037
				]
			]
		},
		{
			"type": "rectangle",
			"version": 1855,
			"versionNonce": 290934914,
			"isDeleted": false,
			"id": "fReMnbw9meZ5mtxesVx9X",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2601.4653646703305,
			"y": 175.94868453319106,
			"strokeColor": "#0091e2",
			"backgroundColor": "#0091e2",
			"width": 5.566352494330056,
			"height": 5.566352494330056,
			"seed": 1025021673,
			"groupIds": [
				"OiCzvWt7tMx1qqWgWWHBO",
				"cjcvIptBcxq1OcqRfgYEu"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029729,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 1910,
			"versionNonce": 1323659422,
			"isDeleted": false,
			"id": "mqK0RzKkmnOna53SFMg_A",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2608.4233033417972,
			"y": 175.69356422872198,
			"strokeColor": "#0091e2",
			"backgroundColor": "#0091e2",
			"width": 5.566352494330056,
			"height": 5.566352494330056,
			"seed": 1637339593,
			"groupIds": [
				"OiCzvWt7tMx1qqWgWWHBO",
				"cjcvIptBcxq1OcqRfgYEu"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029729,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 1930,
			"versionNonce": 282980418,
			"isDeleted": false,
			"id": "zSoSYDbk42TRJtJoUHwGr",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2615.7059398747956,
			"y": 175.80951774041438,
			"strokeColor": "#0091e2",
			"backgroundColor": "#0091e2",
			"width": 5.566352494330056,
			"height": 5.566352494330056,
			"seed": 1814868137,
			"groupIds": [
				"OiCzvWt7tMx1qqWgWWHBO",
				"cjcvIptBcxq1OcqRfgYEu"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029729,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 1951,
			"versionNonce": 1751755998,
			"isDeleted": false,
			"id": "USj-NSFfEuMJqjP2HPkqz",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2622.965382591147,
			"y": 175.4616338480128,
			"strokeColor": "#0091e2",
			"backgroundColor": "#0091e2",
			"width": 5.566352494330056,
			"height": 5.566352494330056,
			"seed": 1384297353,
			"groupIds": [
				"OiCzvWt7tMx1qqWgWWHBO",
				"cjcvIptBcxq1OcqRfgYEu"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029729,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 1993,
			"versionNonce": 1845139458,
			"isDeleted": false,
			"id": "kq6eo1nLaCBkRjWmsLe9o",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2629.853735919786,
			"y": 175.55440132882865,
			"strokeColor": "#0091e2",
			"backgroundColor": "#0091e2",
			"width": 5.566352494330056,
			"height": 5.566352494330056,
			"seed": 1221941865,
			"groupIds": [
				"OiCzvWt7tMx1qqWgWWHBO",
				"cjcvIptBcxq1OcqRfgYEu"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029729,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 1897,
			"versionNonce": 1989959966,
			"isDeleted": false,
			"id": "W5ykAjTzOs6K6ab946a_m",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2608.2261539538454,
			"y": 168.94437379997208,
			"strokeColor": "#0091e2",
			"backgroundColor": "#0091e2",
			"width": 5.566352494330056,
			"height": 5.566352494330056,
			"seed": 1878009161,
			"groupIds": [
				"OiCzvWt7tMx1qqWgWWHBO",
				"cjcvIptBcxq1OcqRfgYEu"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029729,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 1921,
			"versionNonce": 413943746,
			"isDeleted": false,
			"id": "RxD0fTpoXKeTkVkCgEGUI",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2615.531988196379,
			"y": 169.03714517367376,
			"strokeColor": "#0091e2",
			"backgroundColor": "#0091e2",
			"width": 5.566352494330056,
			"height": 5.566352494330056,
			"seed": 1127126057,
			"groupIds": [
				"OiCzvWt7tMx1qqWgWWHBO",
				"cjcvIptBcxq1OcqRfgYEu"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029729,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 1945,
			"versionNonce": 1290702174,
			"isDeleted": false,
			"id": "o6HOHzQqVGLzqggturk_k",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2622.9305938126167,
			"y": 169.03713738790594,
			"strokeColor": "#0091e2",
			"backgroundColor": "#0091e2",
			"width": 5.566352494330056,
			"height": 5.566352494330056,
			"seed": 1182541577,
			"groupIds": [
				"OiCzvWt7tMx1qqWgWWHBO",
				"cjcvIptBcxq1OcqRfgYEu"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029729,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 1964,
			"versionNonce": 689045378,
			"isDeleted": false,
			"id": "SnY9pkry_H43ZJZExqt3j",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2622.687056791369,
			"y": 161.94004360232185,
			"strokeColor": "#0091e2",
			"backgroundColor": "#0091e2",
			"width": 5.566352494330056,
			"height": 5.566352494330056,
			"seed": 1951686121,
			"groupIds": [
				"OiCzvWt7tMx1qqWgWWHBO",
				"cjcvIptBcxq1OcqRfgYEu"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029729,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 258,
			"versionNonce": 682701214,
			"isDeleted": false,
			"id": "a6uVyY8oYAy_NOC8oul3o",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2586.1879913523057,
			"y": 248.43736450166813,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 78,
			"height": 99,
			"seed": 1976617607,
			"groupIds": [
				"cjcvIptBcxq1OcqRfgYEu"
			],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"type": "text",
					"id": "mYyxAIog"
				},
				{
					"id": "HhA7U0xRTPUBRrwc9Aqfo",
					"type": "arrow"
				},
				{
					"id": "m_58e-L9qciWVDHxXtHNo",
					"type": "arrow"
				}
			],
			"updated": 1700563029729,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 224,
			"versionNonce": 1533722434,
			"isDeleted": false,
			"id": "mYyxAIog",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2607.888003559337,
			"y": 261.9373645016681,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 34.5999755859375,
			"height": 72,
			"seed": 310632871,
			"groupIds": [
				"cjcvIptBcxq1OcqRfgYEu"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029729,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 3,
			"text": "서버\n\n",
			"rawText": "서버\n\n",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "a6uVyY8oYAy_NOC8oul3o",
			"originalText": "서버\n\n",
			"lineHeight": 1.2,
			"baseline": 68
		},
		{
			"type": "line",
			"version": 2908,
			"versionNonce": 1964330462,
			"isDeleted": false,
			"id": "QKEDTUDu3zFuTPIsQiSp4",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2607.7503233573593,
			"y": 316.8599699465211,
			"strokeColor": "#0091e2",
			"backgroundColor": "#0091e2",
			"width": 56.62135476067269,
			"height": 27.78137540135306,
			"seed": 1392972999,
			"groupIds": [
				"JtWtXbC49S0NuEIQI4AZf",
				"cjcvIptBcxq1OcqRfgYEu"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1700563029729,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					26.49928798736996,
					-0.5555399791810629
				],
				[
					32.86897029257218,
					-1.351746926303818
				],
				[
					31.54797965057393,
					-6.47281952059744
				],
				[
					33.64708101980081,
					-11.340553540806383
				],
				[
					36.88620050527203,
					-6.798543885447785
				],
				[
					36.45191491873459,
					-3.1432192393850187
				],
				[
					41.67251763363534,
					-6.7171136294920615
				],
				[
					45.75309251293886,
					-5.2242237812582175
				],
				[
					43.32826283037451,
					-1.9398610124836608
				],
				[
					37.99003529362133,
					0.5844902862542796
				],
				[
					24.0563885094017,
					14.925301714362618
				],
				[
					0.1701084154921375,
					16.440821860546677
				],
				[
					-10.868262247733824,
					1.1146897259718145
				],
				[
					-3.582944626162501,
					-0.5971552103421658
				],
				[
					-0.28719357028327863,
					-0.019545320337599037
				]
			]
		},
		{
			"type": "rectangle",
			"version": 1813,
			"versionNonce": 202737410,
			"isDeleted": false,
			"id": "S72AniJ2N-FI0pbEzAIH_",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2601.4653646703287,
			"y": 309.04773197375596,
			"strokeColor": "#0091e2",
			"backgroundColor": "#0091e2",
			"width": 5.566352494330056,
			"height": 5.566352494330056,
			"seed": 2130109415,
			"groupIds": [
				"JtWtXbC49S0NuEIQI4AZf",
				"cjcvIptBcxq1OcqRfgYEu"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029729,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 1868,
			"versionNonce": 254534174,
			"isDeleted": false,
			"id": "-aAUV7Yr5g0MoP2yZyIE9",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2608.4233033417972,
			"y": 308.7926116692869,
			"strokeColor": "#0091e2",
			"backgroundColor": "#0091e2",
			"width": 5.566352494330056,
			"height": 5.566352494330056,
			"seed": 912248583,
			"groupIds": [
				"JtWtXbC49S0NuEIQI4AZf",
				"cjcvIptBcxq1OcqRfgYEu"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029729,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 1888,
			"versionNonce": 865162946,
			"isDeleted": false,
			"id": "Oiswue9zJ-b94IymUqvkf",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2615.705939874794,
			"y": 308.9085651809793,
			"strokeColor": "#0091e2",
			"backgroundColor": "#0091e2",
			"width": 5.566352494330056,
			"height": 5.566352494330056,
			"seed": 1673418279,
			"groupIds": [
				"JtWtXbC49S0NuEIQI4AZf",
				"cjcvIptBcxq1OcqRfgYEu"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029729,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 1909,
			"versionNonce": 166063710,
			"isDeleted": false,
			"id": "OtfYHmzlqdQkCBXE04FZB",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2622.965382591147,
			"y": 308.5606812885777,
			"strokeColor": "#0091e2",
			"backgroundColor": "#0091e2",
			"width": 5.566352494330056,
			"height": 5.566352494330056,
			"seed": 1845426503,
			"groupIds": [
				"JtWtXbC49S0NuEIQI4AZf",
				"cjcvIptBcxq1OcqRfgYEu"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029729,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 1951,
			"versionNonce": 1652371074,
			"isDeleted": false,
			"id": "4PYSxL82WlAB2ynwnTlrv",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2629.853735919786,
			"y": 308.65344876939355,
			"strokeColor": "#0091e2",
			"backgroundColor": "#0091e2",
			"width": 5.566352494330056,
			"height": 5.566352494330056,
			"seed": 712915047,
			"groupIds": [
				"JtWtXbC49S0NuEIQI4AZf",
				"cjcvIptBcxq1OcqRfgYEu"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029729,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 1855,
			"versionNonce": 1913942686,
			"isDeleted": false,
			"id": "gpeVzjCA4PkEE-pzIfKxd",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2608.2261539538435,
			"y": 302.043421240537,
			"strokeColor": "#0091e2",
			"backgroundColor": "#0091e2",
			"width": 5.566352494330056,
			"height": 5.566352494330056,
			"seed": 252220295,
			"groupIds": [
				"JtWtXbC49S0NuEIQI4AZf",
				"cjcvIptBcxq1OcqRfgYEu"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029729,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 1879,
			"versionNonce": 1033375298,
			"isDeleted": false,
			"id": "M69pLI6YVOHNmnqLOD0PS",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2615.5319881963774,
			"y": 302.13619261423867,
			"strokeColor": "#0091e2",
			"backgroundColor": "#0091e2",
			"width": 5.566352494330056,
			"height": 5.566352494330056,
			"seed": 601524903,
			"groupIds": [
				"JtWtXbC49S0NuEIQI4AZf",
				"cjcvIptBcxq1OcqRfgYEu"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029729,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 1903,
			"versionNonce": 308834014,
			"isDeleted": false,
			"id": "kR6rLYj50THzR-sD_xoUc",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2622.9305938126167,
			"y": 302.13618482847085,
			"strokeColor": "#0091e2",
			"backgroundColor": "#0091e2",
			"width": 5.566352494330056,
			"height": 5.566352494330056,
			"seed": 899718599,
			"groupIds": [
				"JtWtXbC49S0NuEIQI4AZf",
				"cjcvIptBcxq1OcqRfgYEu"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029729,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 1922,
			"versionNonce": 2042689026,
			"isDeleted": false,
			"id": "VfkwhZ1fwkR24atOY3m2R",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2622.687056791369,
			"y": 295.03909104288675,
			"strokeColor": "#0091e2",
			"backgroundColor": "#0091e2",
			"width": 5.566352494330056,
			"height": 5.566352494330056,
			"seed": 1199000807,
			"groupIds": [
				"JtWtXbC49S0NuEIQI4AZf",
				"cjcvIptBcxq1OcqRfgYEu"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029729,
			"link": null,
			"locked": false
		},
		{
			"type": "arrow",
			"version": 173,
			"versionNonce": 269096493,
			"isDeleted": false,
			"id": "eWU6nwSpXBYruJ7FZ5nJS",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2483.0725742124287,
			"y": -47.05567807798394,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 92.34600521150014,
			"height": 86.43524677319112,
			"seed": 1050919273,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1700975447992,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "B6rz698sncOsPUlTjK4Vo",
				"gap": 1,
				"focus": 0.3786259987198145
			},
			"endBinding": {
				"elementId": "XooU3nfaAi13KPy-Zlgz4",
				"gap": 10.76941192837694,
				"focus": -0.5835265986314996
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					92.34600521150014,
					86.43524677319112
				]
			]
		},
		{
			"type": "arrow",
			"version": 210,
			"versionNonce": 728903405,
			"isDeleted": false,
			"id": "pJkTtNK1k1c2Z8Ynzh5pK",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2484.7861613456457,
			"y": -45.049934046410876,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 93.60122000444017,
			"height": 212.96452097669922,
			"seed": 97133831,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [
				{
					"type": "text",
					"id": "hcYqJUg5"
				}
			],
			"updated": 1700975447994,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "B6rz698sncOsPUlTjK4Vo",
				"gap": 3.005744031573073,
				"focus": 0.17199403530652782
			},
			"endBinding": {
				"elementId": "3EkOZNHTojwr7UPD2829O",
				"gap": 7.800610002219855,
				"focus": -0.7925581435343386
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					93.60122000444017,
					212.96452097669922
				]
			]
		},
		{
			"type": "text",
			"version": 66,
			"versionNonce": 1940180830,
			"isDeleted": false,
			"id": "hcYqJUg5",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2514.286783554897,
			"y": 49.432326441938855,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 34.5999755859375,
			"height": 24,
			"seed": 353137223,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029729,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 3,
			"text": "배포",
			"rawText": "배포",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "pJkTtNK1k1c2Z8Ynzh5pK",
			"originalText": "배포",
			"lineHeight": 1.2,
			"baseline": 20
		},
		{
			"type": "arrow",
			"version": 176,
			"versionNonce": 12261293,
			"isDeleted": false,
			"id": "HhA7U0xRTPUBRrwc9Aqfo",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2483.4596039238895,
			"y": -46.37649146816656,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 98.64549658033229,
			"height": 349.81151293037647,
			"seed": 1721889383,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1700975447996,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "B6rz698sncOsPUlTjK4Vo",
				"gap": 1.6791866098173784,
				"focus": 0.10717862350128732
			},
			"endBinding": {
				"elementId": "a6uVyY8oYAy_NOC8oul3o",
				"gap": 4.0828908480839345,
				"focus": -0.8427910251460615
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					98.64549658033229,
					349.81151293037647
				]
			]
		},
		{
			"type": "rectangle",
			"version": 210,
			"versionNonce": 1666134942,
			"isDeleted": false,
			"id": "b__CgdGkNvizqsd0cuDmh",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2779.849474049537,
			"y": -7.3857783882069725,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 113.44248898604242,
			"height": 351.56458375102613,
			"seed": 2022843399,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [],
			"updated": 1700563029729,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 215,
			"versionNonce": 589684034,
			"isDeleted": false,
			"id": "UBQybXu5",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2789.695718542558,
			"y": 144.3965134873061,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 93.75,
			"height": 48,
			"seed": 963323625,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "4R7e3vGvMDJKts_sRHLuZ",
					"type": "arrow"
				},
				{
					"id": "VdW1hKzXFvvpuy4eOJcF5",
					"type": "arrow"
				},
				{
					"id": "m_58e-L9qciWVDHxXtHNo",
					"type": "arrow"
				}
			],
			"updated": 1700563029729,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 3,
			"text": "Road \nbalancer",
			"rawText": "Road \nbalancer",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Road \nbalancer",
			"lineHeight": 1.2,
			"baseline": 44
		},
		{
			"type": "arrow",
			"version": 336,
			"versionNonce": 1545652365,
			"isDeleted": false,
			"id": "4R7e3vGvMDJKts_sRHLuZ",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2779.496844861473,
			"y": 161.7748346885518,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 114.30885350916742,
			"height": 135.87684030415681,
			"seed": 567503401,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1700975447992,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "UBQybXu5",
				"gap": 10.198873681084933,
				"focus": -0.7679554540785485
			},
			"endBinding": {
				"elementId": "XooU3nfaAi13KPy-Zlgz4",
				"gap": 1,
				"focus": -0.5990825921916741
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					-114.30885350916742,
					-135.87684030415681
				]
			]
		},
		{
			"type": "arrow",
			"version": 171,
			"versionNonce": 747096397,
			"isDeleted": false,
			"id": "VdW1hKzXFvvpuy4eOJcF5",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2780.037542949834,
			"y": 160.88551178159298,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 114.1040885103107,
			"height": 0.9168358889603212,
			"seed": 2076060839,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1700975447995,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "UBQybXu5",
				"gap": 9.658175592724092,
				"focus": 0.3267574617581601
			},
			"endBinding": {
				"elementId": "3EkOZNHTojwr7UPD2829O",
				"gap": 1.7454630872175585,
				"focus": -0.054374483866678446
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					-114.1040885103107,
					0.9168358889603212
				]
			]
		},
		{
			"type": "arrow",
			"version": 207,
			"versionNonce": 1647680013,
			"isDeleted": false,
			"id": "m_58e-L9qciWVDHxXtHNo",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2778.6807601691016,
			"y": 163.54198499832415,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 111.57187510270614,
			"height": 140.53784412205624,
			"seed": 1223954985,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1700975447997,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "UBQybXu5",
				"gap": 11.014958373456466,
				"focus": 0.9365299566019097
			},
			"endBinding": {
				"elementId": "a6uVyY8oYAy_NOC8oul3o",
				"gap": 2.9208937140897433,
				"focus": 0.597685167020507
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					-111.57187510270614,
					140.53784412205624
				]
			]
		},
		{
			"type": "text",
			"version": 106,
			"versionNonce": 27063490,
			"isDeleted": false,
			"id": "aW0Fy5JH",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2916.743483228288,
			"y": 155.3408375959761,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 51.89996337890625,
			"height": 24,
			"seed": 126694537,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029729,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 3,
			"text": "사용자",
			"rawText": "사용자",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "사용자",
			"lineHeight": 1.2,
			"baseline": 20
		},
		{
			"type": "text",
			"version": 104,
			"versionNonce": 711667806,
			"isDeleted": false,
			"id": "ceeGdHKt",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2210.8604496861335,
			"y": 67.69065493672824,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 51.89996337890625,
			"height": 24,
			"seed": 420239815,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029729,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 3,
			"text": "개발자",
			"rawText": "개발자",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "개발자",
			"lineHeight": 1.2,
			"baseline": 20
		},
		{
			"type": "rectangle",
			"version": 129,
			"versionNonce": 1768230018,
			"isDeleted": false,
			"id": "QynvITMNVFEPW7seKd2si",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2279.411563845319,
			"y": 23.81015044898038,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 89.62154773917337,
			"height": 96.8588420274863,
			"seed": 775815753,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"id": "YDjsdo27rdOcu5FNRq4tn",
					"type": "arrow"
				}
			],
			"updated": 1700563029729,
			"link": null,
			"locked": false
		},
		{
			"type": "arrow",
			"version": 210,
			"versionNonce": 346125470,
			"isDeleted": false,
			"id": "YDjsdo27rdOcu5FNRq4tn",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2350.8609540930493,
			"y": 20.256991582606986,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 79.87554865579295,
			"height": 114.68508707730768,
			"seed": 753362633,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [
				{
					"type": "text",
					"id": "77SKHQNe"
				}
			],
			"updated": 1700563029729,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "QynvITMNVFEPW7seKd2si",
				"focus": -0.12179746241799938,
				"gap": 3.553158866373394
			},
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					79.87554865579295,
					-114.68508707730768
				]
			]
		},
		{
			"type": "text",
			"version": 81,
			"versionNonce": 399780930,
			"isDeleted": false,
			"id": "77SKHQNe",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2364.8487467314926,
			"y": -61.08555195604686,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 51.89996337890625,
			"height": 48,
			"seed": 2090298569,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029729,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 3,
			"text": "이미지\n업로드",
			"rawText": "이미지\n업로드",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "YDjsdo27rdOcu5FNRq4tn",
			"originalText": "이미지\n업로드",
			"lineHeight": 1.2,
			"baseline": 44
		},
		{
			"type": "text",
			"version": 179,
			"versionNonce": 537211102,
			"isDeleted": false,
			"id": "IRAEh0ev",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2227.700296168764,
			"y": -205.7087894460032,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 531.8309326171875,
			"height": 24,
			"seed": 117800295,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029729,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 3,
			"text": "컨테이너만으로 배포한다면 모든 과정을 수동으로 처리해야 함.",
			"rawText": "컨테이너만으로 배포한다면 모든 과정을 수동으로 처리해야 함.",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "컨테이너만으로 배포한다면 모든 과정을 수동으로 처리해야 함.",
			"lineHeight": 1.2,
			"baseline": 20
		},
		{
			"type": "text",
			"version": 83,
			"versionNonce": 852055042,
			"isDeleted": false,
			"id": "YVK2ZMzT",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2365.644522107414,
			"y": 620.3333653038546,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 51.89996337890625,
			"height": 24,
			"seed": 1126213639,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029729,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 3,
			"text": "마스터",
			"rawText": "마스터",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "마스터",
			"lineHeight": 1.2,
			"baseline": 20
		},
		{
			"type": "text",
			"version": 95,
			"versionNonce": 942105886,
			"isDeleted": false,
			"id": "BanCZrTO",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2349.184188935063,
			"y": 668.4482489896182,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 164.0625,
			"height": 24,
			"seed": 931282887,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "DDFALHs8v6U0AXOa5bSVO",
					"type": "arrow"
				}
			],
			"updated": 1700563029729,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 3,
			"text": "kube-apiserver",
			"rawText": "kube-apiserver",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "kube-apiserver",
			"lineHeight": 1.2,
			"baseline": 20
		},
		{
			"type": "text",
			"version": 74,
			"versionNonce": 1279493058,
			"isDeleted": false,
			"id": "UkSGEpJ6",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2356.9317526670525,
			"y": 723.052540728825,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 69.199951171875,
			"height": 24,
			"seed": 1803322119,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029729,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 3,
			"text": "인그레스",
			"rawText": "인그레스",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "인그레스",
			"lineHeight": 1.2,
			"baseline": 20
		},
		{
			"type": "text",
			"version": 118,
			"versionNonce": 779686238,
			"isDeleted": false,
			"id": "u8G9gjbY",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2667.528058698558,
			"y": 501.4299222608985,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 115.5186767578125,
			"height": 24,
			"seed": 1688909513,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029729,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 3,
			"text": "인그레스 노드",
			"rawText": "인그레스 노드",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "인그레스 노드",
			"lineHeight": 1.2,
			"baseline": 20
		},
		{
			"type": "text",
			"version": 196,
			"versionNonce": 1583463298,
			"isDeleted": false,
			"id": "yAv6QMVL",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2701.197541700282,
			"y": 561.5480313993905,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 69.199951171875,
			"height": 48,
			"seed": 821057737,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "OSBPIgEzpzPjmVXKSQzav",
					"type": "arrow"
				}
			],
			"updated": 1700563029729,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 3,
			"text": "인그레스\n컨트롤러",
			"rawText": "인그레스\n컨트롤러",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "인그레스\n컨트롤러",
			"lineHeight": 1.2,
			"baseline": 44
		},
		{
			"type": "text",
			"version": 146,
			"versionNonce": 2118858142,
			"isDeleted": false,
			"id": "0iyoJJ1D",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2821.4138678095937,
			"y": 575.7788881519804,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 58.59375,
			"height": 24,
			"seed": 135848871,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "OSBPIgEzpzPjmVXKSQzav",
					"type": "arrow"
				},
				{
					"id": "QZzEfbV4dw5DZUevBiVHH",
					"type": "arrow"
				},
				{
					"id": "mcX4scicfDjfnHXeulm2p",
					"type": "arrow"
				},
				{
					"id": "8-wGPqpOaaguYnHpkh8S8",
					"type": "arrow"
				}
			],
			"updated": 1700563029729,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 3,
			"text": "nginx",
			"rawText": "nginx",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "nginx",
			"lineHeight": 1.2,
			"baseline": 20
		},
		{
			"type": "arrow",
			"version": 147,
			"versionNonce": 1197669186,
			"isDeleted": false,
			"id": "OSBPIgEzpzPjmVXKSQzav",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2777.6391636304643,
			"y": 587.503331777891,
			"strokeColor": "#1971c2",
			"backgroundColor": "transparent",
			"width": 40.480561212636985,
			"height": 1.61524401497104,
			"seed": 163381863,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1700563029729,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "yAv6QMVL",
				"focus": 0.14281987976907493,
				"gap": 7.241670758307464
			},
			"endBinding": {
				"elementId": "0iyoJJ1D",
				"focus": 0.24232964547263888,
				"gap": 3.2941429664924726
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					40.480561212636985,
					-1.61524401497104
				]
			]
		},
		{
			"type": "arrow",
			"version": 224,
			"versionNonce": 281989598,
			"isDeleted": false,
			"id": "DDFALHs8v6U0AXOa5bSVO",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2669.668455940071,
			"y": 584.4898296545679,
			"strokeColor": "#1971c2",
			"backgroundColor": "transparent",
			"width": 145.21451758866533,
			"height": 112.87124063202305,
			"seed": 1957216423,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029729,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "7rCt97yhdjw82vBYq9270",
				"focus": 0.08965002785068027,
				"gap": 9.405016875348565
			},
			"endBinding": {
				"elementId": "BanCZrTO",
				"focus": 0.7791836178272812,
				"gap": 11.477922838838367
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					-72.4620960352554,
					-0.020069389770924317
				],
				[
					-71.20566248349542,
					112.85117124225212
				],
				[
					-145.21451758866533,
					110.43637680325048
				]
			]
		},
		{
			"type": "rectangle",
			"version": 115,
			"versionNonce": 1168524034,
			"isDeleted": false,
			"id": "AlVdndY_PtzjlpCLPf6vN",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2324.686548870647,
			"y": 597.3976959779726,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 206.16640418673796,
			"height": 194.22712514996897,
			"seed": 1043423143,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [],
			"updated": 1700563029730,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 132,
			"versionNonce": 18146846,
			"isDeleted": false,
			"id": "P1X4Aqjx",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2657.02499416771,
			"y": 674.2331828280619,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 51.89996337890625,
			"height": 24,
			"seed": 1158846889,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029730,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 3,
			"text": "서비스",
			"rawText": "서비스",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "서비스",
			"lineHeight": 1.2,
			"baseline": 20
		},
		{
			"type": "rectangle",
			"version": 137,
			"versionNonce": 1940558530,
			"isDeleted": false,
			"id": "xR6s8tT_v3KHm92Pb34aH",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "dashed",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2645.2329171717142,
			"y": 655.96023760451,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 269.70198773128914,
			"height": 53.02058371310193,
			"seed": 2089047303,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [],
			"updated": 1700563029730,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 171,
			"versionNonce": 1611559518,
			"isDeleted": false,
			"id": "DTIdtZZnMHx-EDuRFnHSV",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2648.614585675964,
			"y": 721.8590106685017,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 168.28773850560583,
			"height": 94.05812562055642,
			"seed": 946453545,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [],
			"updated": 1700563029730,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 101,
			"versionNonce": 1141828226,
			"isDeleted": false,
			"id": "gryp126b",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2663.649086002505,
			"y": 736.9492090645247,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 34.5999755859375,
			"height": 24,
			"seed": 49124809,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029730,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 3,
			"text": "노드",
			"rawText": "노드",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "노드",
			"lineHeight": 1.2,
			"baseline": 20
		},
		{
			"type": "text",
			"version": 109,
			"versionNonce": 2022471326,
			"isDeleted": false,
			"id": "8fr6gYs0",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "dashed",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2679.531202221316,
			"y": 774.100325100444,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 34.530792236328125,
			"height": 23.95855369670802,
			"seed": 1262425575,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029730,
			"link": null,
			"locked": false,
			"fontSize": 19.96546141392335,
			"fontFamily": 3,
			"text": "피드",
			"rawText": "피드",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "피드",
			"lineHeight": 1.2,
			"baseline": 19
		},
		{
			"type": "rectangle",
			"version": 157,
			"versionNonce": 2106739266,
			"isDeleted": false,
			"id": "6kX_8_ZNBsFXxFL2cRmgW",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2661.2540690147894,
			"y": 762.8925741424218,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 73.59306351954365,
			"height": 45.83580928651141,
			"seed": 1612540519,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"id": "8-wGPqpOaaguYnHpkh8S8",
					"type": "arrow"
				}
			],
			"updated": 1700563029730,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 197,
			"versionNonce": 322958046,
			"isDeleted": false,
			"id": "pFrE1jho",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "dashed",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2756.2075517300286,
			"y": 772.073174946383,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 34.530792236328125,
			"height": 23.95855369670802,
			"seed": 322066761,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "mcX4scicfDjfnHXeulm2p",
					"type": "arrow"
				}
			],
			"updated": 1700563029730,
			"link": null,
			"locked": false,
			"fontSize": 19.96546141392335,
			"fontFamily": 3,
			"text": "피드",
			"rawText": "피드",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "피드",
			"lineHeight": 1.2,
			"baseline": 19
		},
		{
			"type": "rectangle",
			"version": 246,
			"versionNonce": 924037634,
			"isDeleted": false,
			"id": "W_mXCDq70CesYTwh553yd",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2737.930418523502,
			"y": 760.8654239883608,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 73.59306351954365,
			"height": 45.83580928651141,
			"seed": 671762473,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"id": "975kMjZK9Uxb_-B1TSJkH",
					"type": "arrow"
				}
			],
			"updated": 1700563029730,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 216,
			"versionNonce": 985261854,
			"isDeleted": false,
			"id": "1o5zqA0-4SfX8kDFwgxh8",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2855.5806550031184,
			"y": 722.6507189418496,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 168.28773850560583,
			"height": 94.05812562055642,
			"seed": 1089821481,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [],
			"updated": 1700563029730,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 146,
			"versionNonce": 1402085826,
			"isDeleted": false,
			"id": "Yy6neeqM",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2870.6151553296595,
			"y": 737.7409173378726,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 34.5999755859375,
			"height": 24,
			"seed": 231869961,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029730,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 3,
			"text": "노드",
			"rawText": "노드",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "노드",
			"lineHeight": 1.2,
			"baseline": 20
		},
		{
			"type": "text",
			"version": 156,
			"versionNonce": 2137740126,
			"isDeleted": false,
			"id": "XKN5fyi8",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "dashed",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2886.497271548471,
			"y": 774.892033373792,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 34.530792236328125,
			"height": 23.95855369670802,
			"seed": 1180001513,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029730,
			"link": null,
			"locked": false,
			"fontSize": 19.96546141392335,
			"fontFamily": 3,
			"text": "피드",
			"rawText": "피드",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "피드",
			"lineHeight": 1.2,
			"baseline": 19
		},
		{
			"type": "rectangle",
			"version": 201,
			"versionNonce": 2116852098,
			"isDeleted": false,
			"id": "T1DX_3CcCNDtarv4CXUJK",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2868.2201383419433,
			"y": 763.6842824157698,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 73.59306351954365,
			"height": 45.83580928651141,
			"seed": 101375945,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [],
			"updated": 1700563029730,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 232,
			"versionNonce": 1000683422,
			"isDeleted": false,
			"id": "1HzLnpNV",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2933.1680657912116,
			"y": 706.8603162437705,
			"strokeColor": "#e03131",
			"backgroundColor": "transparent",
			"width": 80.918701171875,
			"height": 24,
			"seed": 2048671559,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "QZzEfbV4dw5DZUevBiVHH",
					"type": "arrow"
				},
				{
					"id": "975kMjZK9Uxb_-B1TSJkH",
					"type": "arrow"
				}
			],
			"updated": 1700563029730,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 3,
			"text": "장애 발생",
			"rawText": "장애 발생",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "장애 발생",
			"lineHeight": 1.2,
			"baseline": 20
		},
		{
			"type": "arrow",
			"version": 101,
			"versionNonce": 639768898,
			"isDeleted": false,
			"id": "QZzEfbV4dw5DZUevBiVHH",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2859.5471532369265,
			"y": 604.670272478877,
			"strokeColor": "#e03131",
			"backgroundColor": "transparent",
			"width": 91.1658044410392,
			"height": 99.61201883459489,
			"seed": 1613212809,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1700563029730,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "0iyoJJ1D",
				"focus": 0.16441996587126387,
				"gap": 4.8913843268966275
			},
			"endBinding": {
				"elementId": "1HzLnpNV",
				"focus": -0.1860842768749953,
				"gap": 2.578024930298625
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					91.1658044410392,
					99.61201883459489
				]
			]
		},
		{
			"type": "arrow",
			"version": 115,
			"versionNonce": 1469617118,
			"isDeleted": false,
			"id": "mcX4scicfDjfnHXeulm2p",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2829.927715573233,
			"y": 604.0854427493185,
			"strokeColor": "#1971c2",
			"backgroundColor": "transparent",
			"width": 35.36031725384919,
			"height": 160.9952698370297,
			"seed": 1076075047,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1700563029730,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "0iyoJJ1D",
				"focus": 0.5386838698435839,
				"gap": 4.306554597338163
			},
			"endBinding": {
				"elementId": "pFrE1jho",
				"focus": 0.8507828366456951,
				"gap": 6.992462360034722
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					-35.36031725384919,
					160.9952698370297
				]
			]
		},
		{
			"type": "arrow",
			"version": 116,
			"versionNonce": 2060558594,
			"isDeleted": false,
			"id": "8-wGPqpOaaguYnHpkh8S8",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2827.890757603614,
			"y": 606.8623893563378,
			"strokeColor": "#1971c2",
			"backgroundColor": "transparent",
			"width": 111.32452715990212,
			"height": 153.61925406423086,
			"seed": 1406683209,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1700563029730,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "0iyoJJ1D",
				"focus": 0.2366379163504863,
				"gap": 7.08350120435739
			},
			"endBinding": {
				"elementId": "6kX_8_ZNBsFXxFL2cRmgW",
				"focus": 0.0030030053454243376,
				"gap": 2.4109307218532194
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					-111.32452715990212,
					153.61925406423086
				]
			]
		},
		{
			"type": "text",
			"version": 186,
			"versionNonce": 223766558,
			"isDeleted": false,
			"id": "5BtDYdp6",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2428.8699209375864,
			"y": 1189.6695726968123,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 140.625,
			"height": 168,
			"seed": 1299887977,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029730,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 3,
			"text": "bin\n\nhome     me \n\nusr\n\nvar",
			"rawText": "bin\n\nhome     me \n\nusr\n\nvar",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "bin\n\nhome     me \n\nusr\n\nvar",
			"lineHeight": 1.2,
			"baseline": 164
		},
		{
			"type": "text",
			"version": 138,
			"versionNonce": 1740255426,
			"isDeleted": false,
			"id": "e6ZNbbDn",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2610.5752733195395,
			"y": 1199.3712150820193,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 46.875,
			"height": 96,
			"seed": 131977895,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029730,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 3,
			"text": "test\n\n\nwork",
			"rawText": "test\n\n\nwork",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "test\n\n\nwork",
			"lineHeight": 1.2,
			"baseline": 92
		},
		{
			"type": "text",
			"version": 162,
			"versionNonce": 751809630,
			"isDeleted": false,
			"id": "UGQV08on",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2689.5300506788135,
			"y": 1176.3004876299406,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 35.15625,
			"height": 72,
			"seed": 43532839,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029730,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 3,
			"text": "bin\nusr\nvar",
			"rawText": "bin\nusr\nvar",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "bin\nusr\nvar",
			"lineHeight": 1.2,
			"baseline": 68
		},
		{
			"type": "line",
			"version": 241,
			"versionNonce": 276482178,
			"isDeleted": false,
			"id": "M0QbnI7ahGz81cikoSC3y",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2421.873248499075,
			"y": 1201.1258212648818,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 31.23156317407029,
			"height": 148.29024389359984,
			"seed": 1580786665,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029730,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-30.808776590057732,
					-0.2120604102951802
				],
				[
					-31.23156317407029,
					147.82087866903066
				],
				[
					-0.4161185409566315,
					148.07818348330466
				]
			]
		},
		{
			"type": "line",
			"version": 203,
			"versionNonce": 1607825566,
			"isDeleted": false,
			"id": "Wu7m_QuSP_yU4COQGuUOE",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2367.0256238891384,
			"y": 1248.7049458355814,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 54.88363486828848,
			"height": 0.34809916406948105,
			"seed": 828396903,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029730,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					54.88363486828848,
					0.34809916406948105
				]
			]
		},
		{
			"type": "line",
			"version": 312,
			"versionNonce": 1288857666,
			"isDeleted": false,
			"id": "ICmpNGPdtJQh_7wYbpGvV",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2392.0089397887864,
			"y": 1299.8874662014073,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 31.73878301709783,
			"height": 0.039082372474467775,
			"seed": 2103248711,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029730,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					31.73878301709783,
					-0.039082372474467775
				]
			]
		},
		{
			"type": "text",
			"version": 208,
			"versionNonce": 1847112926,
			"isDeleted": false,
			"id": "wPjoA1Pv",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2344.519259114246,
			"y": 1234.3748068610084,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 11.71875,
			"height": 24,
			"seed": 155306121,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029730,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 3,
			"text": "\\",
			"rawText": "\\",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "\\",
			"lineHeight": 1.2,
			"baseline": 20
		},
		{
			"type": "line",
			"version": 158,
			"versionNonce": 614469634,
			"isDeleted": false,
			"id": "F8xFoZxb-5n6RVWheQXmj",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2482.8999323038643,
			"y": 1251.508328617435,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 37.73281629250869,
			"height": 0.6570847471892876,
			"seed": 2027834633,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029730,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					37.73281629250869,
					0.6570847471892876
				]
			]
		},
		{
			"type": "line",
			"version": 182,
			"versionNonce": 19556638,
			"isDeleted": false,
			"id": "0mQhrCTYLaamrdNrk934O",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2564.600946384809,
			"y": 1254.5835835674457,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 18.475362387584482,
			"height": 0.06585470507559421,
			"seed": 904238633,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029730,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					18.475362387584482,
					0.06585470507559421
				]
			]
		},
		{
			"type": "line",
			"version": 312,
			"versionNonce": 1273151426,
			"isDeleted": false,
			"id": "AQJ2TIgT1bI3BcDlIlScj",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2605.104595799769,
			"y": 1212.2704578760568,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 22.45391443220342,
			"height": 75.25852348571493,
			"seed": 20329705,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029730,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-21.573670721964845,
					-0.2349353286040241
				],
				[
					-21.03405363907723,
					74.97373674075243
				],
				[
					0.8802437102385738,
					75.02358815711091
				]
			]
		},
		{
			"type": "line",
			"version": 278,
			"versionNonce": 1752929630,
			"isDeleted": false,
			"id": "SBuwEWZwN9iUXZPb84T4c",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2659.505223852905,
			"y": 1211.7381825221883,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 27.590217652932097,
			"height": 0.444174605642047,
			"seed": 1418812743,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029730,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					27.590217652932097,
					0.444174605642047
				]
			]
		},
		{
			"type": "line",
			"version": 291,
			"versionNonce": 515471234,
			"isDeleted": false,
			"id": "71CJJou7HYhEIxoMhXTYz",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2684.9941316759714,
			"y": 1189.993408224453,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 13.648274246088931,
			"height": 46.82916181820099,
			"seed": 1684778665,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029730,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-13.375054941922372,
					-0.06016088832382138
				],
				[
					-13.239187081460386,
					46.72867814896722
				],
				[
					0.2732193041665596,
					46.769000929877166
				]
			]
		},
		{
			"type": "rectangle",
			"version": 424,
			"versionNonce": 1566390686,
			"isDeleted": false,
			"id": "zJAzs7X1JH6iQvzWmTn2u",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2596.501737020245,
			"y": 1167.6418064875293,
			"strokeColor": "#e03131",
			"backgroundColor": "transparent",
			"width": 160.07259717573152,
			"height": 95.89648643917403,
			"seed": 909842311,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029730,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 110,
			"versionNonce": 493041474,
			"isDeleted": false,
			"id": "lXrmn7zG",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2610.9749669456755,
			"y": 1134.3392450957772,
			"strokeColor": "#e03131",
			"backgroundColor": "transparent",
			"width": 46.875,
			"height": 24,
			"seed": 1385974249,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029730,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 3,
			"text": "jail",
			"rawText": "jail",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "jail",
			"lineHeight": 1.2,
			"baseline": 20
		},
		{
			"type": "text",
			"version": 235,
			"versionNonce": 1191204318,
			"isDeleted": false,
			"id": "U62GSmr4",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2334.936205781143,
			"y": 1046.2130664458768,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 207.6328125,
			"height": 70.87909667982647,
			"seed": 560434537,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029730,
			"link": null,
			"locked": false,
			"fontSize": 59.0659138998554,
			"fontFamily": 3,
			"text": "chroot",
			"rawText": "chroot",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "chroot",
			"lineHeight": 1.2,
			"baseline": 57
		},
		{
			"type": "rectangle",
			"version": 138,
			"versionNonce": 1748958978,
			"isDeleted": false,
			"id": "loJcprsdRe9J0AlkabLob",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2342.736050698828,
			"y": 666.7421745035099,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 174.53647462234267,
			"height": 32.89073932242377,
			"seed": 1306455785,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029730,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 127,
			"versionNonce": 2121656862,
			"isDeleted": false,
			"id": "1LApwuwgJjCj_A8PaC57M",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2351.739446183815,
			"y": 717.722980599042,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 81.8120707481421,
			"height": 37.67269217161822,
			"seed": 1277940201,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029730,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 181,
			"versionNonce": 1003212482,
			"isDeleted": false,
			"id": "K8ts8cY50TJMTHDJJDMq3",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2319.9316608673216,
			"y": 500.3423181814519,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffffff",
			"width": 198,
			"height": 55,
			"seed": 395720775,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"type": "text",
					"id": "y8OsAhjI"
				}
			],
			"updated": 1700563029730,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 91,
			"versionNonce": 313456222,
			"isDeleted": false,
			"id": "y8OsAhjI",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2335.2223407989623,
			"y": 515.8423181814519,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 167.41864013671875,
			"height": 24,
			"seed": 1329335655,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029730,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 3,
			"text": "쿠버네티스 클러스터",
			"rawText": "쿠버네티스 클러스터",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "K8ts8cY50TJMTHDJJDMq3",
			"originalText": "쿠버네티스 클러스터",
			"lineHeight": 1.2,
			"baseline": 20
		},
		{
			"type": "arrow",
			"version": 236,
			"versionNonce": 1822992002,
			"isDeleted": false,
			"id": "975kMjZK9Uxb_-B1TSJkH",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2946.653265599532,
			"y": 740.0397464386,
			"strokeColor": "#e03131",
			"backgroundColor": "#ffffff",
			"width": 125.55798368583646,
			"height": 38.113719211594,
			"seed": 746042249,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029730,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "1HzLnpNV",
				"focus": -0.5350258963582283,
				"gap": 9.179430194829479
			},
			"endBinding": {
				"elementId": "W_mXCDq70CesYTwh553yd",
				"focus": 0.24775715781708207,
				"gap": 9.571799870650011
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					-125.55798368583646,
					38.113719211594
				]
			]
		},
		{
			"type": "rectangle",
			"version": 196,
			"versionNonce": 209484446,
			"isDeleted": false,
			"id": "7UEwuTumejffSFnOiNM80",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2300.2145378352043,
			"y": 1606.4169072441387,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffffff",
			"width": 263.9500605595276,
			"height": 209.1107497843593,
			"seed": 2101765677,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029730,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 82,
			"versionNonce": 1670678082,
			"isDeleted": false,
			"id": "4PyXeiMC",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2302.170873153531,
			"y": 1578.92158677458,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffffff",
			"width": 86.49993896484375,
			"height": 24,
			"seed": 712542467,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029730,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 3,
			"text": "워드프레스",
			"rawText": "워드프레스",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "워드프레스",
			"lineHeight": 1.2,
			"baseline": 20
		},
		{
			"type": "text",
			"version": 188,
			"versionNonce": 848262878,
			"isDeleted": false,
			"id": "mU3dGRbB",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2339.6444400813275,
			"y": 1626.253202629989,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffffff",
			"width": 144.53741455078125,
			"height": 144,
			"seed": 1682961443,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "g4b_Hb7lHfq8J5TH4Y_7T",
					"type": "arrow"
				}
			],
			"updated": 1700563029730,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 3,
			"text": "워드프레스(본체)\n아파치\nPHP 런타임\n\n\nMySQL",
			"rawText": "워드프레스(본체)\n아파치\nPHP 런타임\n\n\nMySQL",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "워드프레스(본체)\n아파치\nPHP 런타임\n\n\nMySQL",
			"lineHeight": 1.2,
			"baseline": 140
		},
		{
			"type": "arrow",
			"version": 268,
			"versionNonce": 1721006307,
			"isDeleted": false,
			"id": "pHzW3WvSqCeWO47wmeP1Z",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2411.826716273013,
			"y": 1760.8123937638375,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffffff",
			"width": 314.9808146748419,
			"height": 0.6280486077284877,
			"seed": 744024611,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700975448002,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": {
				"elementId": "SeAPxyy3DG_GN08TL7ksO",
				"gap": 16.663092128490916,
				"focus": 0.024419848926860423
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					314.9808146748419,
					0.6280486077284877
				]
			]
		},
		{
			"type": "arrow",
			"version": 364,
			"versionNonce": 166776941,
			"isDeleted": false,
			"id": "g4b_Hb7lHfq8J5TH4Y_7T",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2492.9966889251064,
			"y": 1662.3477599458683,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffffff",
			"width": 234.02380103341557,
			"height": 2.1721697078021407,
			"seed": 1907254627,
			"groupIds": [],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1700975448000,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "mU3dGRbB",
				"gap": 8.814834292997602,
				"focus": -0.5044399342893862
			},
			"endBinding": {
				"elementId": "2hPBSKNNRzeVOfm59R23U",
				"gap": 18.025842646621186,
				"focus": -0.10092792693550942
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					234.02380103341557,
					2.1721697078021407
				]
			]
		},
		{
			"type": "rectangle",
			"version": 322,
			"versionNonce": 322264514,
			"isDeleted": false,
			"id": "2hPBSKNNRzeVOfm59R23U",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2745.046332605143,
			"y": 1620.0957973800867,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffffff",
			"width": 131,
			"height": 82,
			"seed": 1283409507,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"type": "text",
					"id": "pTzeYQff"
				},
				{
					"id": "g4b_Hb7lHfq8J5TH4Y_7T",
					"type": "arrow"
				}
			],
			"updated": 1700563029730,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 333,
			"versionNonce": 1806292830,
			"isDeleted": false,
			"id": "pTzeYQff",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2761.4369881227212,
			"y": 1637.0957973800867,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffffff",
			"width": 98.21868896484375,
			"height": 48,
			"seed": 401025411,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029730,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 3,
			"text": "워드프레스 \n컨테이너",
			"rawText": "워드프레스 컨테이너",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "2hPBSKNNRzeVOfm59R23U",
			"originalText": "워드프레스 컨테이너",
			"lineHeight": 1.2,
			"baseline": 44
		},
		{
			"type": "rectangle",
			"version": 1025,
			"versionNonce": 1577604482,
			"isDeleted": false,
			"id": "SeAPxyy3DG_GN08TL7ksO",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2743.470623076346,
			"y": 1721.6086726337476,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffffff",
			"width": 131,
			"height": 82,
			"seed": 1736635299,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"type": "text",
					"id": "ecxbFovw"
				},
				{
					"id": "pHzW3WvSqCeWO47wmeP1Z",
					"type": "arrow"
				}
			],
			"updated": 1700563029730,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 1089,
			"versionNonce": 628308894,
			"isDeleted": false,
			"id": "ecxbFovw",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2774.3706474904084,
			"y": 1738.6086726337476,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffffff",
			"width": 69.199951171875,
			"height": 48,
			"seed": 1858766659,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029730,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 3,
			"text": "MySQL\n컨테이너",
			"rawText": "MySQL\n컨테이너",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "SeAPxyy3DG_GN08TL7ksO",
			"originalText": "MySQL\n컨테이너",
			"lineHeight": 1.2,
			"baseline": 44
		},
		{
			"type": "line",
			"version": 132,
			"versionNonce": 187061570,
			"isDeleted": false,
			"id": "HeKQEgGT2906F0ktgd8Vh",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2492.2516721621087,
			"y": 1632.7024423680596,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffffff",
			"width": 0.02696083910359448,
			"height": 61.38535363604183,
			"seed": 1598828365,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029730,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-0.02696083910359448,
					61.38535363604183
				]
			]
		},
		{
			"type": "rectangle",
			"version": 438,
			"versionNonce": 1627789278,
			"isDeleted": false,
			"id": "4aq35NZsGPLEjgTzgqdwH",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 3779.9943508757938,
			"y": -112.6964078033276,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffd43b",
			"width": 29.879757606580824,
			"height": 20.42211595681351,
			"seed": 770520510,
			"groupIds": [
				"HUU0-JmO_nZvg9BW_ceWK",
				"bEmqepvh_KjoFx3gV9RUA",
				"R31-wm50QwzC5ul7CfaoL"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029730,
			"link": null,
			"locked": false
		},
		{
			"type": "line",
			"version": 604,
			"versionNonce": 737041666,
			"isDeleted": false,
			"id": "nsEZyckVuz89ZrQtlD-W6",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 3787.531723526046,
			"y": -113.7576983855649,
			"strokeColor": "#868e96",
			"backgroundColor": "#ffffff",
			"width": 14.122197119795926,
			"height": 15.423576311625013,
			"seed": 1881533858,
			"groupIds": [
				"HUU0-JmO_nZvg9BW_ceWK",
				"bEmqepvh_KjoFx3gV9RUA",
				"R31-wm50QwzC5ul7CfaoL"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1700563029730,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					1.312511586522962,
					-15.423576311625013
				],
				[
					12.441053632756804,
					-15.177474702843114
				],
				[
					14.122197119795926,
					-0.1644400963632961
				]
			]
		},
		{
			"type": "line",
			"version": 694,
			"versionNonce": 376663070,
			"isDeleted": false,
			"id": "jDZFZBQ7rzzopy3fQ_W8o",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 3687.230694781881,
			"y": -206.70611765704706,
			"strokeColor": "#343a40",
			"backgroundColor": "#e9ecef",
			"width": 47.8552484343013,
			"height": 52.1409014456067,
			"seed": 757851070,
			"groupIds": [
				"vhKgGN_3MwVCdJS3JbuQT",
				"bEmqepvh_KjoFx3gV9RUA",
				"R31-wm50QwzC5ul7CfaoL"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029730,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0.26000176697561983,
					51.87051303094144
				],
				[
					47.8552484343013,
					52.1004585898349
				],
				[
					47.27816454942922,
					17.778207710641695
				],
				[
					28.413767803534483,
					17.53208573341469
				],
				[
					28.33449951749526,
					-0.04044285577180062
				],
				[
					0,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 216,
			"versionNonce": 1306488002,
			"isDeleted": false,
			"id": "09TReDV0CarTAd4ksIs6R",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 3715.66060525337,
			"y": -206.69690112380363,
			"strokeColor": "#343a40",
			"backgroundColor": "#ced4da",
			"width": 18.692645001729034,
			"height": 17.71678984752976,
			"seed": 1369796706,
			"groupIds": [
				"vhKgGN_3MwVCdJS3JbuQT",
				"bEmqepvh_KjoFx3gV9RUA",
				"R31-wm50QwzC5ul7CfaoL"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029730,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					18.692645001729034,
					17.71678984752976
				]
			]
		},
		{
			"type": "line",
			"version": 216,
			"versionNonce": 330053726,
			"isDeleted": false,
			"id": "-krf7hsrTyXN-1IYDZ8xz",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 3692.0615893677314,
			"y": -199.40716403280885,
			"strokeColor": "#ffffff",
			"backgroundColor": "#e9ecef",
			"width": 19.157691418740797,
			"height": 0.09682495328969765,
			"seed": 705033854,
			"groupIds": [
				"vhKgGN_3MwVCdJS3JbuQT",
				"bEmqepvh_KjoFx3gV9RUA",
				"R31-wm50QwzC5ul7CfaoL"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029730,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					19.157691418740797,
					-0.09682495328969765
				]
			]
		},
		{
			"type": "line",
			"version": 218,
			"versionNonce": 1989706882,
			"isDeleted": false,
			"id": "WbGpVYKVZkw2rZamZoklr",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 3692.0615893677314,
			"y": -181.4774860084334,
			"strokeColor": "#ffffff",
			"backgroundColor": "#e9ecef",
			"width": 33.62470437348702,
			"height": 0.03753566471142733,
			"seed": 809195582,
			"groupIds": [
				"vhKgGN_3MwVCdJS3JbuQT",
				"bEmqepvh_KjoFx3gV9RUA",
				"R31-wm50QwzC5ul7CfaoL"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029730,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					33.62470437348702,
					0.03753566471142733
				]
			]
		},
		{
			"type": "line",
			"version": 280,
			"versionNonce": 1082227870,
			"isDeleted": false,
			"id": "4SwXb-prdxWFYVKuapA6e",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 3692.0615893677314,
			"y": -190.39391254397628,
			"strokeColor": "#ffffff",
			"backgroundColor": "#e9ecef",
			"width": 19.157691418740797,
			"height": 0.09682495328969765,
			"seed": 270324734,
			"groupIds": [
				"vhKgGN_3MwVCdJS3JbuQT",
				"bEmqepvh_KjoFx3gV9RUA",
				"R31-wm50QwzC5ul7CfaoL"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029730,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					19.157691418740797,
					-0.09682495328969765
				]
			]
		},
		{
			"type": "line",
			"version": 311,
			"versionNonce": 534291522,
			"isDeleted": false,
			"id": "xy9VpHtObpR0riMLaLk9P",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 3692.0615893677314,
			"y": -172.5235238081791,
			"strokeColor": "#ffffff",
			"backgroundColor": "#e9ecef",
			"width": 33.62470437348702,
			"height": 0.03753566471142733,
			"seed": 1219077474,
			"groupIds": [
				"vhKgGN_3MwVCdJS3JbuQT",
				"bEmqepvh_KjoFx3gV9RUA",
				"R31-wm50QwzC5ul7CfaoL"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029730,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					33.62470437348702,
					0.03753566471142733
				]
			]
		},
		{
			"type": "line",
			"version": 243,
			"versionNonce": 1654929630,
			"isDeleted": false,
			"id": "5orrkm7RFgrx8vvlVa0-W",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 3692.0615893677314,
			"y": -163.5695616079248,
			"strokeColor": "#ffffff",
			"backgroundColor": "#e9ecef",
			"width": 33.62470437348702,
			"height": 0.03753566471142733,
			"seed": 803341694,
			"groupIds": [
				"vhKgGN_3MwVCdJS3JbuQT",
				"bEmqepvh_KjoFx3gV9RUA",
				"R31-wm50QwzC5ul7CfaoL"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029730,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					33.62470437348702,
					0.03753566471142733
				]
			]
		},
		{
			"type": "text",
			"version": 125,
			"versionNonce": 863947778,
			"isDeleted": false,
			"id": "4dcxyexb",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 3580.40365311097,
			"y": -113.12997899047771,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffd43b",
			"width": 70.3125,
			"height": 24,
			"seed": 1648794110,
			"groupIds": [
				"bEmqepvh_KjoFx3gV9RUA",
				"R31-wm50QwzC5ul7CfaoL"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029730,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 3,
			"text": "sender",
			"rawText": "sender",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "sender",
			"lineHeight": 1.2,
			"baseline": 20
		},
		{
			"type": "line",
			"version": 725,
			"versionNonce": 1638231326,
			"isDeleted": false,
			"id": "YNzK6iWJFRr05Eq3YHutu",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 3844.320959360927,
			"y": -203.6677690628098,
			"strokeColor": "#343a40",
			"backgroundColor": "#e9ecef",
			"width": 47.8552484343013,
			"height": 52.1409014456067,
			"seed": 1162016482,
			"groupIds": [
				"-oE9oSPLaCYwDmhHX_oGV",
				"bEmqepvh_KjoFx3gV9RUA",
				"R31-wm50QwzC5ul7CfaoL"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029730,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0.26000176697561983,
					51.87051303094144
				],
				[
					47.8552484343013,
					52.1004585898349
				],
				[
					47.27816454942922,
					17.778207710641695
				],
				[
					28.413767803534483,
					17.53208573341469
				],
				[
					28.33449951749526,
					-0.04044285577180062
				],
				[
					0,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 247,
			"versionNonce": 126483394,
			"isDeleted": false,
			"id": "zGVKve9KkvTMOGnJ1IRqU",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 3872.7508698324154,
			"y": -203.6585525295664,
			"strokeColor": "#343a40",
			"backgroundColor": "#ced4da",
			"width": 18.692645001729034,
			"height": 17.71678984752976,
			"seed": 1766181538,
			"groupIds": [
				"-oE9oSPLaCYwDmhHX_oGV",
				"bEmqepvh_KjoFx3gV9RUA",
				"R31-wm50QwzC5ul7CfaoL"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029730,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					18.692645001729034,
					17.71678984752976
				]
			]
		},
		{
			"type": "line",
			"version": 247,
			"versionNonce": 183900510,
			"isDeleted": false,
			"id": "lLjNzih2wXCMwPuY_P26c",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 3849.151853946777,
			"y": -196.3688154385716,
			"strokeColor": "#ffffff",
			"backgroundColor": "#e9ecef",
			"width": 19.157691418740797,
			"height": 0.09682495328969765,
			"seed": 1966614114,
			"groupIds": [
				"-oE9oSPLaCYwDmhHX_oGV",
				"bEmqepvh_KjoFx3gV9RUA",
				"R31-wm50QwzC5ul7CfaoL"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029731,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					19.157691418740797,
					-0.09682495328969765
				]
			]
		},
		{
			"type": "line",
			"version": 260,
			"versionNonce": 1511601026,
			"isDeleted": false,
			"id": "nxD8g_b3WUQKmM5-4OIvw",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 3849.151853946777,
			"y": -178.43913741419615,
			"strokeColor": "#ffffff",
			"backgroundColor": "#e9ecef",
			"width": 33.62470437348702,
			"height": 0.03753566471142733,
			"seed": 1374226978,
			"groupIds": [
				"-oE9oSPLaCYwDmhHX_oGV",
				"bEmqepvh_KjoFx3gV9RUA",
				"R31-wm50QwzC5ul7CfaoL"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029731,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					33.62470437348702,
					0.03753566471142733
				]
			]
		},
		{
			"type": "line",
			"version": 311,
			"versionNonce": 1441217950,
			"isDeleted": false,
			"id": "uPQm0go2ImEDSJPfudOC-",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 3849.151853946777,
			"y": -187.35556394973904,
			"strokeColor": "#ffffff",
			"backgroundColor": "#e9ecef",
			"width": 19.157691418740797,
			"height": 0.09682495328969765,
			"seed": 1984394722,
			"groupIds": [
				"-oE9oSPLaCYwDmhHX_oGV",
				"bEmqepvh_KjoFx3gV9RUA",
				"R31-wm50QwzC5ul7CfaoL"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029731,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					19.157691418740797,
					-0.09682495328969765
				]
			]
		},
		{
			"type": "line",
			"version": 342,
			"versionNonce": 1298887490,
			"isDeleted": false,
			"id": "U6rz0lpV50h0Aj3t7NziU",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 3849.151853946777,
			"y": -169.4851752139419,
			"strokeColor": "#ffffff",
			"backgroundColor": "#e9ecef",
			"width": 33.62470437348702,
			"height": 0.03753566471142733,
			"seed": 593652130,
			"groupIds": [
				"-oE9oSPLaCYwDmhHX_oGV",
				"bEmqepvh_KjoFx3gV9RUA",
				"R31-wm50QwzC5ul7CfaoL"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029731,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					33.62470437348702,
					0.03753566471142733
				]
			]
		},
		{
			"type": "line",
			"version": 274,
			"versionNonce": 665442782,
			"isDeleted": false,
			"id": "-Bm_r_ggXJVyorg6Gxwkj",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 3849.151853946777,
			"y": -160.5312130136876,
			"strokeColor": "#ffffff",
			"backgroundColor": "#e9ecef",
			"width": 33.62470437348702,
			"height": 0.03753566471142733,
			"seed": 543745378,
			"groupIds": [
				"-oE9oSPLaCYwDmhHX_oGV",
				"bEmqepvh_KjoFx3gV9RUA",
				"R31-wm50QwzC5ul7CfaoL"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029731,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					33.62470437348702,
					0.03753566471142733
				]
			]
		},
		{
			"type": "line",
			"version": 781,
			"versionNonce": 1675606786,
			"isDeleted": false,
			"id": "aycXrNaVIUiYS9QzrPnjZ",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 4007.2570131639227,
			"y": -204.4613773565829,
			"strokeColor": "#343a40",
			"backgroundColor": "#e9ecef",
			"width": 47.8552484343013,
			"height": 52.1409014456067,
			"seed": 1096138558,
			"groupIds": [
				"6IB7njOOPyWb3NnMlBQYN",
				"bEmqepvh_KjoFx3gV9RUA",
				"R31-wm50QwzC5ul7CfaoL"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029731,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0.26000176697561983,
					51.87051303094144
				],
				[
					47.8552484343013,
					52.1004585898349
				],
				[
					47.27816454942922,
					17.778207710641695
				],
				[
					28.413767803534483,
					17.53208573341469
				],
				[
					28.33449951749526,
					-0.04044285577180062
				],
				[
					0,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 303,
			"versionNonce": 391048734,
			"isDeleted": false,
			"id": "77_mjSC57E6589ECqhLJI",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 4035.686923635411,
			"y": -204.45216082333945,
			"strokeColor": "#343a40",
			"backgroundColor": "#ced4da",
			"width": 18.692645001729034,
			"height": 17.71678984752976,
			"seed": 1360471934,
			"groupIds": [
				"6IB7njOOPyWb3NnMlBQYN",
				"bEmqepvh_KjoFx3gV9RUA",
				"R31-wm50QwzC5ul7CfaoL"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029731,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					18.692645001729034,
					17.71678984752976
				]
			]
		},
		{
			"type": "line",
			"version": 303,
			"versionNonce": 2079656642,
			"isDeleted": false,
			"id": "r9e3YK8xiGWMQzcrc4cEK",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 4012.0879077497725,
			"y": -197.16242373234468,
			"strokeColor": "#ffffff",
			"backgroundColor": "#e9ecef",
			"width": 19.157691418740797,
			"height": 0.09682495328969765,
			"seed": 1828816830,
			"groupIds": [
				"6IB7njOOPyWb3NnMlBQYN",
				"bEmqepvh_KjoFx3gV9RUA",
				"R31-wm50QwzC5ul7CfaoL"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029731,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					19.157691418740797,
					-0.09682495328969765
				]
			]
		},
		{
			"type": "line",
			"version": 316,
			"versionNonce": 835156574,
			"isDeleted": false,
			"id": "-Bt1bA7yPi-enS_oj1c4e",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 4012.0879077497725,
			"y": -179.23274570796923,
			"strokeColor": "#ffffff",
			"backgroundColor": "#e9ecef",
			"width": 33.62470437348702,
			"height": 0.03753566471142733,
			"seed": 355852286,
			"groupIds": [
				"6IB7njOOPyWb3NnMlBQYN",
				"bEmqepvh_KjoFx3gV9RUA",
				"R31-wm50QwzC5ul7CfaoL"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029731,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					33.62470437348702,
					0.03753566471142733
				]
			]
		},
		{
			"type": "line",
			"version": 367,
			"versionNonce": 1279943298,
			"isDeleted": false,
			"id": "2h2OgDvGOKfX4-HBCbSpX",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 4012.0879077497725,
			"y": -188.1491722435121,
			"strokeColor": "#ffffff",
			"backgroundColor": "#e9ecef",
			"width": 19.157691418740797,
			"height": 0.09682495328969765,
			"seed": 498413630,
			"groupIds": [
				"6IB7njOOPyWb3NnMlBQYN",
				"bEmqepvh_KjoFx3gV9RUA",
				"R31-wm50QwzC5ul7CfaoL"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029731,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					19.157691418740797,
					-0.09682495328969765
				]
			]
		},
		{
			"type": "line",
			"version": 398,
			"versionNonce": 1038384798,
			"isDeleted": false,
			"id": "yL8SR1vrCUlkmJvPn9TQs",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 4012.0879077497725,
			"y": -170.27878350771493,
			"strokeColor": "#ffffff",
			"backgroundColor": "#e9ecef",
			"width": 33.62470437348702,
			"height": 0.03753566471142733,
			"seed": 845183102,
			"groupIds": [
				"6IB7njOOPyWb3NnMlBQYN",
				"bEmqepvh_KjoFx3gV9RUA",
				"R31-wm50QwzC5ul7CfaoL"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029731,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					33.62470437348702,
					0.03753566471142733
				]
			]
		},
		{
			"type": "line",
			"version": 330,
			"versionNonce": 1604239938,
			"isDeleted": false,
			"id": "aCRUPUbxXKCCwgCw8IW5p",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 4012.0879077497725,
			"y": -161.32482130746064,
			"strokeColor": "#ffffff",
			"backgroundColor": "#e9ecef",
			"width": 33.62470437348702,
			"height": 0.03753566471142733,
			"seed": 1526249662,
			"groupIds": [
				"6IB7njOOPyWb3NnMlBQYN",
				"bEmqepvh_KjoFx3gV9RUA",
				"R31-wm50QwzC5ul7CfaoL"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029731,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					33.62470437348702,
					0.03753566471142733
				]
			]
		},
		{
			"type": "rectangle",
			"version": 455,
			"versionNonce": 5700318,
			"isDeleted": false,
			"id": "jD_XyxR9A6Nn-RW3n8DzR",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 3939.1523062471983,
			"y": -111.8397754830069,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffd43b",
			"width": 29.879757606580824,
			"height": 20.42211595681351,
			"seed": 1459440190,
			"groupIds": [
				"N9WNHtSxQCMxTXN5iAXxp",
				"bEmqepvh_KjoFx3gV9RUA",
				"R31-wm50QwzC5ul7CfaoL"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029731,
			"link": null,
			"locked": false
		},
		{
			"type": "line",
			"version": 685,
			"versionNonce": 282143234,
			"isDeleted": false,
			"id": "8kM2DRm6QHj8hBPwZoiVT",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 3960.872914841528,
			"y": -113.47826800451993,
			"strokeColor": "#868e96",
			"backgroundColor": "#ffffff",
			"width": 14.122197119795926,
			"height": 15.423576311625013,
			"seed": 2140492414,
			"groupIds": [
				"N9WNHtSxQCMxTXN5iAXxp",
				"bEmqepvh_KjoFx3gV9RUA",
				"R31-wm50QwzC5ul7CfaoL"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1700563029731,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					1.312511586522962,
					-15.423576311625013
				],
				[
					12.441053632756804,
					-15.177474702843114
				],
				[
					14.122197119795926,
					-0.1644400963632961
				]
			]
		},
		{
			"type": "text",
			"version": 103,
			"versionNonce": 2142236446,
			"isDeleted": false,
			"id": "jbDMTqgs",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 4104.273309726148,
			"y": -115.96493001031665,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffd43b",
			"width": 105.46875,
			"height": 24,
			"seed": 1812026338,
			"groupIds": [
				"bEmqepvh_KjoFx3gV9RUA",
				"R31-wm50QwzC5ul7CfaoL"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029731,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 3,
			"text": "recipient",
			"rawText": "recipient",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "recipient",
			"lineHeight": 1.2,
			"baseline": 20
		},
		{
			"type": "ellipse",
			"version": 484,
			"versionNonce": 115382722,
			"isDeleted": false,
			"id": "pyNLtJrB4-6Qd9gtl-TUV",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 3796.3374923775,
			"y": -50.819055445422705,
			"strokeColor": "#ced4da",
			"backgroundColor": "#ced4da",
			"width": 13.067473882675918,
			"height": 13.067473882675918,
			"seed": 2121093374,
			"groupIds": [
				"bcJ1APQujFsv3bnWfgTud",
				"bEmqepvh_KjoFx3gV9RUA",
				"R31-wm50QwzC5ul7CfaoL"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029731,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 295,
			"versionNonce": 1214274398,
			"isDeleted": false,
			"id": "XhmkFHnqAxQIgGxXbF_4O",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 3779.6024407733303,
			"y": -45.34434301396756,
			"strokeColor": "#ced4da",
			"backgroundColor": "#ced4da",
			"width": 23.970082587564775,
			"height": 2.118049019765664,
			"seed": 1865808382,
			"groupIds": [
				"bcJ1APQujFsv3bnWfgTud",
				"bEmqepvh_KjoFx3gV9RUA",
				"R31-wm50QwzC5ul7CfaoL"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029731,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 372,
			"versionNonce": 820777346,
			"isDeleted": false,
			"id": "3pSgn5uDnbZ4eklNUKufQ",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 3779.5402361091046,
			"y": -43.181558006372924,
			"strokeColor": "#ced4da",
			"backgroundColor": "#ced4da",
			"width": 1.943844261213144,
			"height": 5.792479004576364,
			"seed": 2095460414,
			"groupIds": [
				"bcJ1APQujFsv3bnWfgTud",
				"bEmqepvh_KjoFx3gV9RUA",
				"R31-wm50QwzC5ul7CfaoL"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029731,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 400,
			"versionNonce": 817446814,
			"isDeleted": false,
			"id": "Apzpnl9VNbURuYW7EzRMa",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 3785.7746019377064,
			"y": -43.14913486087325,
			"strokeColor": "#ced4da",
			"backgroundColor": "#ced4da",
			"width": 1.604582208964985,
			"height": 5.72763271357701,
			"seed": 13592190,
			"groupIds": [
				"bcJ1APQujFsv3bnWfgTud",
				"bEmqepvh_KjoFx3gV9RUA",
				"R31-wm50QwzC5ul7CfaoL"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029731,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 255,
			"versionNonce": 1110610242,
			"isDeleted": false,
			"id": "Dp7LOinl5bN-dtdNgzNj_",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 3804.815145020622,
			"y": -45.70008811903752,
			"strokeColor": "#ffffff",
			"backgroundColor": "#ffffff",
			"width": 2.8295392299055493,
			"height": 2.8295392299055493,
			"seed": 1786270818,
			"groupIds": [
				"bcJ1APQujFsv3bnWfgTud",
				"bEmqepvh_KjoFx3gV9RUA",
				"R31-wm50QwzC5ul7CfaoL"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029731,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 535,
			"versionNonce": 485202910,
			"isDeleted": false,
			"id": "jZRrGF90KMtVOGzHAoLB6",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 3956.449757519295,
			"y": -50.73955231506089,
			"strokeColor": "#ced4da",
			"backgroundColor": "#ced4da",
			"width": 13.067473882675918,
			"height": 13.067473882675918,
			"seed": 1119499390,
			"groupIds": [
				"hza8Ub-xyGxHdCFj2Anp4",
				"bEmqepvh_KjoFx3gV9RUA",
				"R31-wm50QwzC5ul7CfaoL"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029731,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 346,
			"versionNonce": 773003522,
			"isDeleted": false,
			"id": "w5P8ncs2rwwFgysOUf88G",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 3939.7147059151253,
			"y": -45.264839883605745,
			"strokeColor": "#ced4da",
			"backgroundColor": "#ced4da",
			"width": 23.970082587564775,
			"height": 2.118049019765664,
			"seed": 817558718,
			"groupIds": [
				"hza8Ub-xyGxHdCFj2Anp4",
				"bEmqepvh_KjoFx3gV9RUA",
				"R31-wm50QwzC5ul7CfaoL"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029731,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 423,
			"versionNonce": 1124626462,
			"isDeleted": false,
			"id": "_yr7PyTkkqvcTYT70AJeB",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 3939.6525012508996,
			"y": -43.10205487601108,
			"strokeColor": "#ced4da",
			"backgroundColor": "#ced4da",
			"width": 1.943844261213144,
			"height": 5.792479004576364,
			"seed": 1496952062,
			"groupIds": [
				"hza8Ub-xyGxHdCFj2Anp4",
				"bEmqepvh_KjoFx3gV9RUA",
				"R31-wm50QwzC5ul7CfaoL"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029731,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 451,
			"versionNonce": 604809410,
			"isDeleted": false,
			"id": "QP6FP3AabYiqdyQqutpWO",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 3945.8868670795005,
			"y": -43.06963173051143,
			"strokeColor": "#ced4da",
			"backgroundColor": "#ced4da",
			"width": 1.604582208964985,
			"height": 5.72763271357701,
			"seed": 699882814,
			"groupIds": [
				"hza8Ub-xyGxHdCFj2Anp4",
				"bEmqepvh_KjoFx3gV9RUA",
				"R31-wm50QwzC5ul7CfaoL"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029731,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 306,
			"versionNonce": 1862319198,
			"isDeleted": false,
			"id": "KrKslfQVUFsbaePt2hPUG",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 3964.9274101624164,
			"y": -45.6205849886757,
			"strokeColor": "#ffffff",
			"backgroundColor": "#ffffff",
			"width": 2.8295392299055493,
			"height": 2.8295392299055493,
			"seed": 932513150,
			"groupIds": [
				"hza8Ub-xyGxHdCFj2Anp4",
				"bEmqepvh_KjoFx3gV9RUA",
				"R31-wm50QwzC5ul7CfaoL"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029731,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 170,
			"versionNonce": 197017730,
			"isDeleted": false,
			"id": "CKxnv7Px",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 3756.024916842768,
			"y": -25.584491570196903,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffffff",
			"width": 76.875,
			"height": 15.748171506430756,
			"seed": 1011025214,
			"groupIds": [
				"bEmqepvh_KjoFx3gV9RUA",
				"R31-wm50QwzC5ul7CfaoL"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029731,
			"link": null,
			"locked": false,
			"fontSize": 13.123476255358964,
			"fontFamily": 3,
			"text": "public key",
			"rawText": "public key",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "public key",
			"lineHeight": 1.2,
			"baseline": 13
		},
		{
			"type": "text",
			"version": 216,
			"versionNonce": 1185251486,
			"isDeleted": false,
			"id": "mClRuRJW",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 3912.303616326435,
			"y": -25.584491570196903,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffffff",
			"width": 84.5625,
			"height": 15.748171506430756,
			"seed": 206515106,
			"groupIds": [
				"bEmqepvh_KjoFx3gV9RUA",
				"R31-wm50QwzC5ul7CfaoL"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029731,
			"link": null,
			"locked": false,
			"fontSize": 13.123476255358964,
			"fontFamily": 3,
			"text": "private key",
			"rawText": "private key",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "private key",
			"lineHeight": 1.2,
			"baseline": 13
		},
		{
			"type": "text",
			"version": 184,
			"versionNonce": 15130690,
			"isDeleted": false,
			"id": "h36ZvW6V",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 3776.1112816403315,
			"y": -79.60522206798218,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffffff",
			"width": 36.71923828125,
			"height": 16.981579190959835,
			"seed": 1543981822,
			"groupIds": [
				"bEmqepvh_KjoFx3gV9RUA",
				"R31-wm50QwzC5ul7CfaoL"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029731,
			"link": null,
			"locked": false,
			"fontSize": 14.15131599246653,
			"fontFamily": 3,
			"text": "암호화",
			"rawText": "암호화",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "암호화",
			"lineHeight": 1.2,
			"baseline": 13
		},
		{
			"type": "text",
			"version": 228,
			"versionNonce": 229096670,
			"isDeleted": false,
			"id": "xcJjrVDC",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 3936.22524718581,
			"y": -79.44621580725855,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffffff",
			"width": 36.71923828125,
			"height": 16.981579190959835,
			"seed": 1629607202,
			"groupIds": [
				"bEmqepvh_KjoFx3gV9RUA",
				"R31-wm50QwzC5ul7CfaoL"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029731,
			"link": null,
			"locked": false,
			"fontSize": 14.15131599246653,
			"fontFamily": 3,
			"text": "복호화",
			"rawText": "복호화",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "복호화",
			"lineHeight": 1.2,
			"baseline": 13
		},
		{
			"type": "arrow",
			"version": 153,
			"versionNonce": 1332054018,
			"isDeleted": false,
			"id": "Hsa3-Xlf0fHoEWaQTGKo3",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 3674.5209203035815,
			"y": -102.937922803803,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffffff",
			"width": 81.66866337960073,
			"height": 0.37075361511153915,
			"seed": 285574754,
			"groupIds": [
				"bEmqepvh_KjoFx3gV9RUA",
				"R31-wm50QwzC5ul7CfaoL"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029731,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					81.66866337960073,
					-0.37075361511153915
				]
			]
		},
		{
			"type": "arrow",
			"version": 180,
			"versionNonce": 1771598110,
			"isDeleted": false,
			"id": "EHso5DONFWkOR3LksCdT0",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 3833.678875674986,
			"y": -101.25667302891854,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffffff",
			"width": 81.66866337960073,
			"height": 0.37075361511153915,
			"seed": 385982498,
			"groupIds": [
				"bEmqepvh_KjoFx3gV9RUA",
				"R31-wm50QwzC5ul7CfaoL"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029731,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					81.66866337960073,
					-0.37075361511153915
				]
			]
		},
		{
			"type": "arrow",
			"version": 169,
			"versionNonce": 1866020802,
			"isDeleted": false,
			"id": "ifrJDYaW4ug5ebf_UP3Q0",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 3998.7998791539358,
			"y": -100.16369994390759,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffffff",
			"width": 81.66866337960073,
			"height": 0.37075361511153915,
			"seed": 96843390,
			"groupIds": [
				"bEmqepvh_KjoFx3gV9RUA",
				"R31-wm50QwzC5ul7CfaoL"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029731,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					81.66866337960073,
					-0.37075361511153915
				]
			]
		},
		{
			"type": "rectangle",
			"version": 581,
			"versionNonce": 636001630,
			"isDeleted": false,
			"id": "giFzH0LTHezbvGR2oJOA2",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 3853.1568167732776,
			"y": -143.54804946703922,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffd43b",
			"width": 29.879757606580824,
			"height": 20.42211595681351,
			"seed": 1871599614,
			"groupIds": [
				"pr3xWTVsvwhpp9eUHuYWG",
				"bEmqepvh_KjoFx3gV9RUA",
				"R31-wm50QwzC5ul7CfaoL"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029731,
			"link": null,
			"locked": false
		},
		{
			"type": "line",
			"version": 327,
			"versionNonce": 8449922,
			"isDeleted": false,
			"id": "0mJFyE7qaDDfQD5hlbAig",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 3862.3756816278274,
			"y": -144.85323685370685,
			"strokeColor": "#868e96",
			"backgroundColor": "#ffffff",
			"width": 3.7894202806219255,
			"height": 13.035203628962847,
			"seed": 66888802,
			"groupIds": [
				"bEmqepvh_KjoFx3gV9RUA",
				"R31-wm50QwzC5ul7CfaoL"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1700563029731,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0.5165119848265931,
					-10.513601486911597
				],
				[
					3.7894202806219255,
					-13.035203628962847
				]
			]
		},
		{
			"type": "line",
			"version": 197,
			"versionNonce": 2011775390,
			"isDeleted": false,
			"id": "yBYMZ7OuiFqHKVuowPlUY",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 3873.31664455845,
			"y": -150.27833610515762,
			"strokeColor": "#868e96",
			"backgroundColor": "#ffffff",
			"width": 0.029394936658718507,
			"height": 5.3446293760354,
			"seed": 623476798,
			"groupIds": [
				"bEmqepvh_KjoFx3gV9RUA",
				"R31-wm50QwzC5ul7CfaoL"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1700563029731,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0.029394936658718507,
					5.3446293760354
				]
			]
		},
		{
			"type": "rectangle",
			"version": 96,
			"versionNonce": 1199288130,
			"isDeleted": false,
			"id": "kChwKuMPcWlnTtwh3CMO6",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 3722.822352386301,
			"y": -55.811601578615125,
			"strokeColor": "#e03131",
			"backgroundColor": "transparent",
			"width": 297.83770161290295,
			"height": 53.59879032258067,
			"seed": 854908834,
			"groupIds": [
				"R31-wm50QwzC5ul7CfaoL"
			],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [],
			"updated": 1700563029731,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 109,
			"versionNonce": 1120624094,
			"isDeleted": false,
			"id": "azd6fyzH",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 3832.3460419024304,
			"y": 5.00997100203017,
			"strokeColor": "#e03131",
			"backgroundColor": "transparent",
			"width": 73.92031860351562,
			"height": 16.063298278753386,
			"seed": 1230320894,
			"groupIds": [
				"R31-wm50QwzC5ul7CfaoL"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029731,
			"link": null,
			"locked": false,
			"fontSize": 13.386081898961155,
			"fontFamily": 3,
			"text": "유일한 pair",
			"rawText": "유일한 pair",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "유일한 pair",
			"lineHeight": 1.2,
			"baseline": 13
		},
		{
			"type": "text",
			"version": 86,
			"versionNonce": 680032002,
			"isDeleted": false,
			"id": "CGyeqbPt",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 3831.8872863479314,
			"y": 373.7134317092876,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 11.71875,
			"height": 24,
			"seed": 1482262782,
			"groupIds": [
				"utWEnkHNdmRq-ErZe34TV"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029731,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 3,
			"text": "",
			"rawText": "",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "",
			"lineHeight": 1.2,
			"baseline": 20
		},
		{
			"type": "text",
			"version": 142,
			"versionNonce": 1537208862,
			"isDeleted": false,
			"id": "olKQEyJ5",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 3698.3993831221255,
			"y": 418.2942028786424,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 80.918701171875,
			"height": 24,
			"seed": 477985342,
			"groupIds": [
				"utWEnkHNdmRq-ErZe34TV"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "UWAmt74s4OJ40icN7sy-B",
					"type": "arrow"
				}
			],
			"updated": 1700563029731,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 3,
			"text": "보내는 이",
			"rawText": "보내는 이",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "보내는 이",
			"lineHeight": 1.2,
			"baseline": 20
		},
		{
			"type": "text",
			"version": 184,
			"versionNonce": 606488258,
			"isDeleted": false,
			"id": "ERvPZNgU",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 3985.7356917552547,
			"y": 418.2942028786424,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 63.61871337890625,
			"height": 24,
			"seed": 1983253182,
			"groupIds": [
				"utWEnkHNdmRq-ErZe34TV"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029731,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 3,
			"text": "받는 이",
			"rawText": "받는 이",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "받는 이",
			"lineHeight": 1.2,
			"baseline": 20
		},
		{
			"type": "text",
			"version": 168,
			"versionNonce": 1297612382,
			"isDeleted": false,
			"id": "SoITUkQB",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 3865.226900231659,
			"y": 263.1520657818682,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 34.5999755859375,
			"height": 24,
			"seed": 1331388862,
			"groupIds": [
				"utWEnkHNdmRq-ErZe34TV"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029731,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 3,
			"text": "해커",
			"rawText": "해커",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "해커",
			"lineHeight": 1.2,
			"baseline": 20
		},
		{
			"type": "text",
			"version": 239,
			"versionNonce": 1391730306,
			"isDeleted": false,
			"id": "l867T5jL",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 3989.643983479675,
			"y": 378.00589642702937,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 55.78125,
			"height": 32.65221774193557,
			"seed": 513874558,
			"groupIds": [
				"utWEnkHNdmRq-ErZe34TV"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029731,
			"link": null,
			"locked": false,
			"fontSize": 13.60509072580649,
			"fontFamily": 3,
			"text": "public\nprivate",
			"rawText": "public\nprivate",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "public\nprivate",
			"lineHeight": 1.2,
			"baseline": 29
		},
		{
			"type": "rectangle",
			"version": 315,
			"versionNonce": 482640542,
			"isDeleted": false,
			"id": "pXMtAZpCHMglTOQ6uY_Wn",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 3968.2103710253527,
			"y": 393.5326101367069,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 98.66935483870994,
			"height": 58.31401209677424,
			"seed": 115869538,
			"groupIds": [
				"utWEnkHNdmRq-ErZe34TV"
			],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"id": "9giQq9iqFjp57A91lWwG9",
					"type": "arrow"
				},
				{
					"id": "UWAmt74s4OJ40icN7sy-B",
					"type": "arrow"
				},
				{
					"id": "Vz3YpTEyE1d9k9wRof27j",
					"type": "arrow"
				}
			],
			"updated": 1700563029731,
			"link": null,
			"locked": false
		},
		{
			"type": "line",
			"version": 818,
			"versionNonce": 1638989378,
			"isDeleted": false,
			"id": "DkJono5H0dKS-iOAx-mL8",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 3789.5801258404595,
			"y": 417.1297768381269,
			"strokeColor": "#343a40",
			"backgroundColor": "#e9ecef",
			"width": 26.42280568632044,
			"height": 28.789086929477673,
			"seed": 1095449506,
			"groupIds": [
				"Rscv8egTO7JRmTosP_QB_",
				"SCsOpXXIWb-vYrsfnWlzI",
				"3TeEv3Nh1cZCFohGU1ZPg",
				"utWEnkHNdmRq-ErZe34TV"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029731,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0.14355742351496317,
					28.63979462039394
				],
				[
					26.42280568632044,
					28.76675680364152
				],
				[
					26.104174483817843,
					9.816062880422235
				],
				[
					15.68838298937526,
					9.680169046575982
				],
				[
					15.644615783318907,
					-0.022330125836150055
				],
				[
					0,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 340,
			"versionNonce": 211189470,
			"isDeleted": false,
			"id": "NQG8QGMtJze2fBTGLa-mY",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 3805.2774218454924,
			"y": 417.13486565648975,
			"strokeColor": "#343a40",
			"backgroundColor": "#ced4da",
			"width": 10.320960454779144,
			"height": 9.782151610169326,
			"seed": 1835497314,
			"groupIds": [
				"Rscv8egTO7JRmTosP_QB_",
				"SCsOpXXIWb-vYrsfnWlzI",
				"3TeEv3Nh1cZCFohGU1ZPg",
				"utWEnkHNdmRq-ErZe34TV"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029731,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					10.320960454779144,
					9.782151610169326
				]
			]
		},
		{
			"type": "line",
			"version": 340,
			"versionNonce": 222029314,
			"isDeleted": false,
			"id": "utPirM1_bKkAce8SYReQF",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 3792.247456867029,
			"y": 421.15982243681344,
			"strokeColor": "#ffffff",
			"backgroundColor": "#e9ecef",
			"width": 10.57773126913801,
			"height": 0.0534609475462874,
			"seed": 168180514,
			"groupIds": [
				"Rscv8egTO7JRmTosP_QB_",
				"SCsOpXXIWb-vYrsfnWlzI",
				"3TeEv3Nh1cZCFohGU1ZPg",
				"utWEnkHNdmRq-ErZe34TV"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029731,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					10.57773126913801,
					-0.0534609475462874
				]
			]
		},
		{
			"type": "line",
			"version": 342,
			"versionNonce": 1633612574,
			"isDeleted": false,
			"id": "JBw4AsyYdi51JMRVCTbze",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 3792.247456867029,
			"y": 431.0595181641643,
			"strokeColor": "#ffffff",
			"backgroundColor": "#e9ecef",
			"width": 18.565550467057946,
			"height": 0.020724948828518188,
			"seed": 1972799202,
			"groupIds": [
				"Rscv8egTO7JRmTosP_QB_",
				"SCsOpXXIWb-vYrsfnWlzI",
				"3TeEv3Nh1cZCFohGU1ZPg",
				"utWEnkHNdmRq-ErZe34TV"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029731,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					18.565550467057946,
					0.020724948828518188
				]
			]
		},
		{
			"type": "line",
			"version": 404,
			"versionNonce": 513004994,
			"isDeleted": false,
			"id": "g7Ft-JzsjieoXHcxVGG6L",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 3792.247456867029,
			"y": 426.13640077426203,
			"strokeColor": "#ffffff",
			"backgroundColor": "#e9ecef",
			"width": 10.57773126913801,
			"height": 0.0534609475462874,
			"seed": 1755798178,
			"groupIds": [
				"Rscv8egTO7JRmTosP_QB_",
				"SCsOpXXIWb-vYrsfnWlzI",
				"3TeEv3Nh1cZCFohGU1ZPg",
				"utWEnkHNdmRq-ErZe34TV"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029731,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					10.57773126913801,
					-0.0534609475462874
				]
			]
		},
		{
			"type": "line",
			"version": 435,
			"versionNonce": 630120286,
			"isDeleted": false,
			"id": "Y9B-EeVMjKXVRzysdApEw",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 3792.247456867029,
			"y": 436.003360502895,
			"strokeColor": "#ffffff",
			"backgroundColor": "#e9ecef",
			"width": 18.565550467057946,
			"height": 0.020724948828518188,
			"seed": 837269090,
			"groupIds": [
				"Rscv8egTO7JRmTosP_QB_",
				"SCsOpXXIWb-vYrsfnWlzI",
				"3TeEv3Nh1cZCFohGU1ZPg",
				"utWEnkHNdmRq-ErZe34TV"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029731,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					18.565550467057946,
					0.020724948828518188
				]
			]
		},
		{
			"type": "line",
			"version": 367,
			"versionNonce": 1725418882,
			"isDeleted": false,
			"id": "zJac0Ha5n9GoJbF4qd5F6",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 3792.247456867029,
			"y": 440.94720284162577,
			"strokeColor": "#ffffff",
			"backgroundColor": "#e9ecef",
			"width": 18.565550467057946,
			"height": 0.020724948828518188,
			"seed": 1915132450,
			"groupIds": [
				"Rscv8egTO7JRmTosP_QB_",
				"SCsOpXXIWb-vYrsfnWlzI",
				"3TeEv3Nh1cZCFohGU1ZPg",
				"utWEnkHNdmRq-ErZe34TV"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029731,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					18.565550467057946,
					0.020724948828518188
				]
			]
		},
		{
			"type": "line",
			"version": 893,
			"versionNonce": 1836532638,
			"isDeleted": false,
			"id": "4PPJHgjZSzON3ntLnX2TR",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 3832.1132118709475,
			"y": 412.56194297208145,
			"strokeColor": "#343a40",
			"backgroundColor": "#e9ecef",
			"width": 22.14708311172035,
			"height": 24.130454142792942,
			"seed": 369935998,
			"groupIds": [
				"B9qGpn8vAEyBITYpLdDAw",
				"lniiHot_KThmIIjyc4pRJ",
				"utWEnkHNdmRq-ErZe34TV"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029731,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0.1203270473103599,
					24.005320225658252
				],
				[
					22.14708311172035,
					24.111737464531767
				],
				[
					21.88001261937419,
					8.227633470246298
				],
				[
					13.149698259866312,
					8.113729895119095
				],
				[
					13.113013436853755,
					-0.0187166782611744
				],
				[
					0,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 415,
			"versionNonce": 994495810,
			"isDeleted": false,
			"id": "eB2AMF9upG8zC0gAmgK-f",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 3845.2703808476217,
			"y": 412.5662083209078,
			"strokeColor": "#343a40",
			"backgroundColor": "#ced4da",
			"width": 8.650828821827663,
			"height": 8.199209701414512,
			"seed": 1609254590,
			"groupIds": [
				"B9qGpn8vAEyBITYpLdDAw",
				"lniiHot_KThmIIjyc4pRJ",
				"utWEnkHNdmRq-ErZe34TV"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029731,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					8.650828821827663,
					8.199209701414512
				]
			]
		},
		{
			"type": "line",
			"version": 415,
			"versionNonce": 457777118,
			"isDeleted": false,
			"id": "9hSlh2-kPGxHcWf1ecUqa",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 3834.348916989972,
			"y": 415.93984900816696,
			"strokeColor": "#ffffff",
			"backgroundColor": "#e9ecef",
			"width": 8.866049136951656,
			"height": 0.044809929066387116,
			"seed": 579845886,
			"groupIds": [
				"B9qGpn8vAEyBITYpLdDAw",
				"lniiHot_KThmIIjyc4pRJ",
				"utWEnkHNdmRq-ErZe34TV"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029731,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					8.866049136951656,
					-0.044809929066387116
				]
			]
		},
		{
			"type": "line",
			"version": 428,
			"versionNonce": 1900008706,
			"isDeleted": false,
			"id": "i7DkuXxAi11TmHMOy890R",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 3834.348916989972,
			"y": 424.23758190819314,
			"strokeColor": "#ffffff",
			"backgroundColor": "#e9ecef",
			"width": 15.561284221290792,
			"height": 0.017371250034547793,
			"seed": 1115369278,
			"groupIds": [
				"B9qGpn8vAEyBITYpLdDAw",
				"lniiHot_KThmIIjyc4pRJ",
				"utWEnkHNdmRq-ErZe34TV"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029731,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					15.561284221290792,
					0.017371250034547793
				]
			]
		},
		{
			"type": "line",
			"version": 479,
			"versionNonce": 588608542,
			"isDeleted": false,
			"id": "ThiajKPGBGp0yo6-6MAtH",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 3834.348916989972,
			"y": 420.1111204227132,
			"strokeColor": "#ffffff",
			"backgroundColor": "#e9ecef",
			"width": 8.866049136951656,
			"height": 0.044809929066387116,
			"seed": 1812895614,
			"groupIds": [
				"B9qGpn8vAEyBITYpLdDAw",
				"lniiHot_KThmIIjyc4pRJ",
				"utWEnkHNdmRq-ErZe34TV"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029731,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					8.866049136951656,
					-0.044809929066387116
				]
			]
		},
		{
			"type": "line",
			"version": 510,
			"versionNonce": 1514267842,
			"isDeleted": false,
			"id": "LxxIPcFjnR0WJsdCPg8me",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 3834.348916989972,
			"y": 428.38141464370756,
			"strokeColor": "#ffffff",
			"backgroundColor": "#e9ecef",
			"width": 15.561284221290792,
			"height": 0.017371250034547793,
			"seed": 394983358,
			"groupIds": [
				"B9qGpn8vAEyBITYpLdDAw",
				"lniiHot_KThmIIjyc4pRJ",
				"utWEnkHNdmRq-ErZe34TV"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029731,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					15.561284221290792,
					0.017371250034547793
				]
			]
		},
		{
			"type": "line",
			"version": 442,
			"versionNonce": 1322074206,
			"isDeleted": false,
			"id": "03bTT9BEZ0L7t0MpsmXzb",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 3834.348916989972,
			"y": 432.52524737922204,
			"strokeColor": "#ffffff",
			"backgroundColor": "#e9ecef",
			"width": 15.561284221290792,
			"height": 0.017371250034547793,
			"seed": 219238398,
			"groupIds": [
				"B9qGpn8vAEyBITYpLdDAw",
				"lniiHot_KThmIIjyc4pRJ",
				"utWEnkHNdmRq-ErZe34TV"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029731,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					15.561284221290792,
					0.017371250034547793
				]
			]
		},
		{
			"type": "rectangle",
			"version": 750,
			"versionNonce": 1072430210,
			"isDeleted": false,
			"id": "o-prMoml5zEkc9O7x3w7G",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 3836.202386514838,
			"y": 440.3849398241151,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffd43b",
			"width": 13.828148358262002,
			"height": 9.451216203248254,
			"seed": 835602174,
			"groupIds": [
				"gGUu151ZrheGmk_aN11k3",
				"lniiHot_KThmIIjyc4pRJ",
				"utWEnkHNdmRq-ErZe34TV"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "Vz3YpTEyE1d9k9wRof27j",
					"type": "arrow"
				}
			],
			"updated": 1700563029731,
			"link": null,
			"locked": false
		},
		{
			"type": "line",
			"version": 495,
			"versionNonce": 37848222,
			"isDeleted": false,
			"id": "JuPxT08dcKXaOxMox4w3U",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 3840.4688143949425,
			"y": 439.78090798905777,
			"strokeColor": "#868e96",
			"backgroundColor": "#ffffff",
			"width": 1.7537179023402085,
			"height": 6.03260347807353,
			"seed": 2024322878,
			"groupIds": [
				"lniiHot_KThmIIjyc4pRJ",
				"utWEnkHNdmRq-ErZe34TV"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1700563029731,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0.2390382294610527,
					-4.865623177232125
				],
				[
					1.7537179023402085,
					-6.03260347807353
				]
			]
		},
		{
			"type": "line",
			"version": 365,
			"versionNonce": 1610423362,
			"isDeleted": false,
			"id": "fXQw3FFSQbt8-X6raDqjK",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 3845.5322175382657,
			"y": 437.270208996947,
			"strokeColor": "#868e96",
			"backgroundColor": "#ffffff",
			"width": 0.013603776524912297,
			"height": 2.4734580817170144,
			"seed": 323690366,
			"groupIds": [
				"lniiHot_KThmIIjyc4pRJ",
				"utWEnkHNdmRq-ErZe34TV"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1700563029731,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0.013603776524912297,
					2.4734580817170144
				]
			]
		},
		{
			"type": "arrow",
			"version": 1789,
			"versionNonce": 2133016798,
			"isDeleted": false,
			"id": "9giQq9iqFjp57A91lWwG9",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "dashed",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 3998.401479834595,
			"y": 374.33702900304206,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 84.512458069486,
			"height": 71.35898877870801,
			"seed": 802771618,
			"groupIds": [
				"utWEnkHNdmRq-ErZe34TV"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1700563029732,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "RhikoFbqNCG3WzbCY0egH",
				"focus": -5.927467232577263,
				"gap": 12.526888681408082
			},
			"endBinding": {
				"elementId": "4OpD0YY7vWmEkI7a9hVPw",
				"focus": -3.3140024242762625,
				"gap": 11.457795311805626
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					-84.512458069486,
					-71.35898877870801
				]
			]
		},
		{
			"type": "arrow",
			"version": 2305,
			"versionNonce": 1750352898,
			"isDeleted": false,
			"id": "UWAmt74s4OJ40icN7sy-B",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "dashed",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 3997.892406456305,
			"y": 374.8295640122932,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 229.02280841820675,
			"height": 27.89889542158653,
			"seed": 779615806,
			"groupIds": [
				"utWEnkHNdmRq-ErZe34TV"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1700563029732,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "RhikoFbqNCG3WzbCY0egH",
				"focus": -0.0961643150918379,
				"gap": 13.035962059698477
			},
			"endBinding": {
				"elementId": "a7_aC3v7T1Dy36m3VQT94",
				"focus": 0.05188962030232457,
				"gap": 8.805348614426626
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					-229.02280841820675,
					27.89889542158653
				]
			]
		},
		{
			"type": "rectangle",
			"version": 146,
			"versionNonce": 688092446,
			"isDeleted": false,
			"id": "o3_gyNGq2Ck5dpQPo_-Kp",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 3694.2814395737437,
			"y": 391.29502193106146,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 88.85584677419365,
			"height": 63.65675403225811,
			"seed": 1516732578,
			"groupIds": [
				"utWEnkHNdmRq-ErZe34TV"
			],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [],
			"updated": 1700563029732,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 194,
			"versionNonce": 1928360898,
			"isDeleted": false,
			"id": "r-IXJ0k3njAa2_W07QmCP",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 3836.7663186060017,
			"y": 250.77964894719042,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 88.85584677419365,
			"height": 63.65675403225811,
			"seed": 1470390846,
			"groupIds": [
				"utWEnkHNdmRq-ErZe34TV"
			],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [],
			"updated": 1700563029732,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 819,
			"versionNonce": 1230184798,
			"isDeleted": false,
			"id": "GvZl6BYSaXHmM-PnKgoe6",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 3753.507609954807,
			"y": 400.0241507048023,
			"strokeColor": "#ced4da",
			"backgroundColor": "#ced4da",
			"width": 7.653166918459806,
			"height": 7.653166918459806,
			"seed": 908814398,
			"groupIds": [
				"ryfLunwJRYgXJYsqr07o-",
				"5RX-bFUcTkvqGPGSqxnlj",
				"z0HH7TK1_QyMPRm6mRcwK",
				"utWEnkHNdmRq-ErZe34TV"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "UWAmt74s4OJ40icN7sy-B",
					"type": "arrow"
				}
			],
			"updated": 1700563029732,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 629,
			"versionNonce": 32549762,
			"isDeleted": false,
			"id": "G6S5aaYhuk3RisrT4_bpT",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 3743.7064697753312,
			"y": 403.23050018326126,
			"strokeColor": "#ced4da",
			"backgroundColor": "#ced4da",
			"width": 14.038447272896667,
			"height": 1.2404679615420366,
			"seed": 1330622590,
			"groupIds": [
				"ryfLunwJRYgXJYsqr07o-",
				"5RX-bFUcTkvqGPGSqxnlj",
				"z0HH7TK1_QyMPRm6mRcwK",
				"utWEnkHNdmRq-ErZe34TV"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029732,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 706,
			"versionNonce": 1399014814,
			"isDeleted": false,
			"id": "_bJxTnTjfA6wNKgWcRGGx",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 3743.6700386576795,
			"y": 404.49716846364004,
			"strokeColor": "#ced4da",
			"backgroundColor": "#ced4da",
			"width": 1.1384422672753027,
			"height": 3.392454355884956,
			"seed": 88142014,
			"groupIds": [
				"ryfLunwJRYgXJYsqr07o-",
				"5RX-bFUcTkvqGPGSqxnlj",
				"z0HH7TK1_QyMPRm6mRcwK",
				"utWEnkHNdmRq-ErZe34TV"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029732,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 736,
			"versionNonce": 2073291586,
			"isDeleted": false,
			"id": "d-RAYhpoAvzxXCpvwCGAX",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 3747.3212908235855,
			"y": 404.5161575771258,
			"strokeColor": "#ced4da",
			"backgroundColor": "#ced4da",
			"width": 0.9397482321261998,
			"height": 3.3544761289134053,
			"seed": 597698814,
			"groupIds": [
				"ryfLunwJRYgXJYsqr07o-",
				"5RX-bFUcTkvqGPGSqxnlj",
				"z0HH7TK1_QyMPRm6mRcwK",
				"utWEnkHNdmRq-ErZe34TV"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029732,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 590,
			"versionNonce": 677700062,
			"isDeleted": false,
			"id": "a7_aC3v7T1Dy36m3VQT94",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 3758.4726775215813,
			"y": 403.02215259489253,
			"strokeColor": "#ffffff",
			"backgroundColor": "#ffffff",
			"width": 1.657163138279252,
			"height": 1.657163138279252,
			"seed": 1508792638,
			"groupIds": [
				"ryfLunwJRYgXJYsqr07o-",
				"5RX-bFUcTkvqGPGSqxnlj",
				"z0HH7TK1_QyMPRm6mRcwK",
				"utWEnkHNdmRq-ErZe34TV"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "UWAmt74s4OJ40icN7sy-B",
					"type": "arrow"
				}
			],
			"updated": 1700563029732,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 862,
			"versionNonce": 641282818,
			"isDeleted": false,
			"id": "wOIMOFjuovJcH7wJ5j0Pl",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 3845.064991196059,
			"y": 454.4636125732511,
			"strokeColor": "#ced4da",
			"backgroundColor": "#ced4da",
			"width": 7.653166918459806,
			"height": 7.653166918459806,
			"seed": 149297762,
			"groupIds": [
				"gXFOy6OhCbmiUfS9sm9bX",
				"hETM1-nzMBLpgTiXXC9uq",
				"iJELzyOuLCPZv0rbB7gSX",
				"utWEnkHNdmRq-ErZe34TV"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029732,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 673,
			"versionNonce": 1533605406,
			"isDeleted": false,
			"id": "KJYIRm2977Vw0xmfX3Ze9",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 3835.2638510165834,
			"y": 457.66996205170994,
			"strokeColor": "#ced4da",
			"backgroundColor": "#ced4da",
			"width": 14.038447272896667,
			"height": 1.2404679615420366,
			"seed": 599293474,
			"groupIds": [
				"gXFOy6OhCbmiUfS9sm9bX",
				"hETM1-nzMBLpgTiXXC9uq",
				"iJELzyOuLCPZv0rbB7gSX",
				"utWEnkHNdmRq-ErZe34TV"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029732,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 750,
			"versionNonce": 610239170,
			"isDeleted": false,
			"id": "nxcYYfZo6ZoIA_wFmuJm5",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 3835.2274198989326,
			"y": 458.9366303320887,
			"strokeColor": "#ced4da",
			"backgroundColor": "#ced4da",
			"width": 1.1384422672753027,
			"height": 3.392454355884956,
			"seed": 1174956514,
			"groupIds": [
				"gXFOy6OhCbmiUfS9sm9bX",
				"hETM1-nzMBLpgTiXXC9uq",
				"iJELzyOuLCPZv0rbB7gSX",
				"utWEnkHNdmRq-ErZe34TV"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029732,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 780,
			"versionNonce": 1969259102,
			"isDeleted": false,
			"id": "m9vjBPA56ItyFzzk6wf5R",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 3838.8786720648386,
			"y": 458.9556194455745,
			"strokeColor": "#ced4da",
			"backgroundColor": "#ced4da",
			"width": 0.9397482321261998,
			"height": 3.3544761289134053,
			"seed": 920968610,
			"groupIds": [
				"gXFOy6OhCbmiUfS9sm9bX",
				"hETM1-nzMBLpgTiXXC9uq",
				"iJELzyOuLCPZv0rbB7gSX",
				"utWEnkHNdmRq-ErZe34TV"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029732,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 633,
			"versionNonce": 1889917570,
			"isDeleted": false,
			"id": "egzhk6u6vRDEOjzmm0ZmF",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 3850.0300587628335,
			"y": 457.46161446334133,
			"strokeColor": "#ffffff",
			"backgroundColor": "#ffffff",
			"width": 1.657163138279252,
			"height": 1.657163138279252,
			"seed": 58513762,
			"groupIds": [
				"gXFOy6OhCbmiUfS9sm9bX",
				"hETM1-nzMBLpgTiXXC9uq",
				"iJELzyOuLCPZv0rbB7gSX",
				"utWEnkHNdmRq-ErZe34TV"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029732,
			"link": null,
			"locked": false
		},
		{
			"type": "arrow",
			"version": 887,
			"versionNonce": 958170782,
			"isDeleted": false,
			"id": "Vz3YpTEyE1d9k9wRof27j",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 3860.1005756516524,
			"y": 429.6216640940715,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 101.11987132590912,
			"height": 0.63534858779866,
			"seed": 2143337890,
			"groupIds": [
				"utWEnkHNdmRq-ErZe34TV"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1700563029732,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "o-prMoml5zEkc9O7x3w7G",
				"focus": -3.2254160242586534,
				"gap": 10.763275730043631
			},
			"endBinding": {
				"elementId": "pXMtAZpCHMglTOQ6uY_Wn",
				"focus": -0.2016767426141422,
				"gap": 6.989924047790964
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					101.11987132590912,
					-0.63534858779866
				]
			]
		},
		{
			"type": "rectangle",
			"version": 714,
			"versionNonce": 1506490946,
			"isDeleted": false,
			"id": "GrnnJgHTOr3Kt0h_Vahv3",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 4082.5811145680786,
			"y": 431.55805432241465,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffd43b",
			"width": 13.99800082718693,
			"height": 9.567306395866549,
			"seed": 404453666,
			"groupIds": [
				"NK1QtH0h95WI-ipwWgozJ",
				"utWEnkHNdmRq-ErZe34TV"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029732,
			"link": null,
			"locked": false
		},
		{
			"type": "line",
			"version": 944,
			"versionNonce": 1733165790,
			"isDeleted": false,
			"id": "AkeU1FPVPhn6RG7LTWQLK",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 4092.756735838967,
			"y": 430.7904570756945,
			"strokeColor": "#868e96",
			"backgroundColor": "transparent",
			"width": 6.615934759827567,
			"height": 7.2256019212403935,
			"seed": 1247020258,
			"groupIds": [
				"NK1QtH0h95WI-ipwWgozJ",
				"utWEnkHNdmRq-ErZe34TV"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1700563029732,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0.6148824403379503,
					-7.2256019212403935
				],
				[
					5.828356485865578,
					-7.110308799768005
				],
				[
					6.615934759827567,
					-0.07703652202349705
				]
			]
		},
		{
			"type": "line",
			"version": 1983,
			"versionNonce": 2125373954,
			"isDeleted": false,
			"id": "Tb_0WRXY8idkIH2mhQ1J7",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 3840.5921230410668,
			"y": 267.4883025643851,
			"strokeColor": "#343a40",
			"backgroundColor": "#e9ecef",
			"width": 22.14708311172035,
			"height": 24.130454142792942,
			"seed": 246282018,
			"groupIds": [
				"qC_ODn-v3Ckyb3BUFNR9R",
				"rmviMtHBaBdKaxSGIOya-",
				"utWEnkHNdmRq-ErZe34TV"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029732,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0.1203270473103599,
					24.005320225658252
				],
				[
					22.14708311172035,
					24.111737464531767
				],
				[
					21.88001261937419,
					8.227633470246298
				],
				[
					13.149698259866312,
					8.113729895119095
				],
				[
					13.113013436853755,
					-0.0187166782611744
				],
				[
					0,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 1505,
			"versionNonce": 42333982,
			"isDeleted": false,
			"id": "wHSne8PYJI2NUxr2D_GL5",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 3853.749292017742,
			"y": 267.49256791321136,
			"strokeColor": "#343a40",
			"backgroundColor": "#ced4da",
			"width": 8.650828821827663,
			"height": 8.199209701414512,
			"seed": 99009250,
			"groupIds": [
				"qC_ODn-v3Ckyb3BUFNR9R",
				"rmviMtHBaBdKaxSGIOya-",
				"utWEnkHNdmRq-ErZe34TV"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029732,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					8.650828821827663,
					8.199209701414512
				]
			]
		},
		{
			"type": "line",
			"version": 1505,
			"versionNonce": 1246695874,
			"isDeleted": false,
			"id": "OQ1XF3SxhcmJGW34a4Nf9",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 3842.8278281600915,
			"y": 270.8662086004706,
			"strokeColor": "#ffffff",
			"backgroundColor": "#e9ecef",
			"width": 8.866049136951656,
			"height": 0.044809929066387116,
			"seed": 2073040546,
			"groupIds": [
				"qC_ODn-v3Ckyb3BUFNR9R",
				"rmviMtHBaBdKaxSGIOya-",
				"utWEnkHNdmRq-ErZe34TV"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029732,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					8.866049136951656,
					-0.044809929066387116
				]
			]
		},
		{
			"type": "line",
			"version": 1518,
			"versionNonce": 322265950,
			"isDeleted": false,
			"id": "y_E0CIa_AyMmwDZ6NMsoM",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 3842.8278281600915,
			"y": 279.1639415004967,
			"strokeColor": "#ffffff",
			"backgroundColor": "#e9ecef",
			"width": 15.561284221290792,
			"height": 0.017371250034547793,
			"seed": 1616441954,
			"groupIds": [
				"qC_ODn-v3Ckyb3BUFNR9R",
				"rmviMtHBaBdKaxSGIOya-",
				"utWEnkHNdmRq-ErZe34TV"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029732,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					15.561284221290792,
					0.017371250034547793
				]
			]
		},
		{
			"type": "line",
			"version": 1569,
			"versionNonce": 1875609986,
			"isDeleted": false,
			"id": "8zaVgPS81fOoihuAufXux",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 3842.8278281600915,
			"y": 275.0374800150168,
			"strokeColor": "#ffffff",
			"backgroundColor": "#e9ecef",
			"width": 8.866049136951656,
			"height": 0.044809929066387116,
			"seed": 923817506,
			"groupIds": [
				"qC_ODn-v3Ckyb3BUFNR9R",
				"rmviMtHBaBdKaxSGIOya-",
				"utWEnkHNdmRq-ErZe34TV"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029732,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					8.866049136951656,
					-0.044809929066387116
				]
			]
		},
		{
			"type": "line",
			"version": 1600,
			"versionNonce": 1806518174,
			"isDeleted": false,
			"id": "15ljqGLJQSJjy1l30kLuE",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 3842.8278281600915,
			"y": 283.30777423601097,
			"strokeColor": "#ffffff",
			"backgroundColor": "#e9ecef",
			"width": 15.561284221290792,
			"height": 0.017371250034547793,
			"seed": 1353007586,
			"groupIds": [
				"qC_ODn-v3Ckyb3BUFNR9R",
				"rmviMtHBaBdKaxSGIOya-",
				"utWEnkHNdmRq-ErZe34TV"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029732,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					15.561284221290792,
					0.017371250034547793
				]
			]
		},
		{
			"type": "line",
			"version": 1532,
			"versionNonce": 1717766466,
			"isDeleted": false,
			"id": "iXzcHSdtSrQoWcf6L46Pw",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 3842.8278281600915,
			"y": 287.4516069715255,
			"strokeColor": "#ffffff",
			"backgroundColor": "#e9ecef",
			"width": 15.561284221290792,
			"height": 0.017371250034547793,
			"seed": 136754594,
			"groupIds": [
				"qC_ODn-v3Ckyb3BUFNR9R",
				"rmviMtHBaBdKaxSGIOya-",
				"utWEnkHNdmRq-ErZe34TV"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029732,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					15.561284221290792,
					0.017371250034547793
				]
			]
		},
		{
			"type": "rectangle",
			"version": 1840,
			"versionNonce": 1813947358,
			"isDeleted": false,
			"id": "o5ozM0g7p0QxAB98erxT3",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 3844.681297684958,
			"y": 295.31129941641893,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffd43b",
			"width": 13.828148358262002,
			"height": 9.451216203248254,
			"seed": 2126754146,
			"groupIds": [
				"BwmV19b6iW3u8j1ILW7Pm",
				"rmviMtHBaBdKaxSGIOya-",
				"utWEnkHNdmRq-ErZe34TV"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029732,
			"link": null,
			"locked": false
		},
		{
			"type": "line",
			"version": 1585,
			"versionNonce": 1702138114,
			"isDeleted": false,
			"id": "2BlSek7C64RPT7bVc4kgj",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 3848.9477255650627,
			"y": 294.7072675813615,
			"strokeColor": "#868e96",
			"backgroundColor": "#ffffff",
			"width": 1.7537179023402085,
			"height": 6.03260347807353,
			"seed": 1472935202,
			"groupIds": [
				"rmviMtHBaBdKaxSGIOya-",
				"utWEnkHNdmRq-ErZe34TV"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1700563029732,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0.2390382294610527,
					-4.865623177232125
				],
				[
					1.7537179023402085,
					-6.03260347807353
				]
			]
		},
		{
			"type": "line",
			"version": 1455,
			"versionNonce": 1184528414,
			"isDeleted": false,
			"id": "IXgl5UVrAmSscJHsmpk1E",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 3854.0111287083855,
			"y": 292.196568589251,
			"strokeColor": "#868e96",
			"backgroundColor": "#ffffff",
			"width": 0.013603776524912297,
			"height": 2.4734580817170144,
			"seed": 1957445858,
			"groupIds": [
				"rmviMtHBaBdKaxSGIOya-",
				"utWEnkHNdmRq-ErZe34TV"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1700563029732,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0.013603776524912297,
					2.4734580817170144
				]
			]
		},
		{
			"type": "ellipse",
			"version": 1214,
			"versionNonce": 1618944194,
			"isDeleted": false,
			"id": "oURrZGJU6-vu2ZUlstXrx",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 3897.1737654015974,
			"y": 293.52353064381435,
			"strokeColor": "#ced4da",
			"backgroundColor": "#ced4da",
			"width": 7.653166918459806,
			"height": 7.653166918459806,
			"seed": 1062563390,
			"groupIds": [
				"2kKSuI-hZGZIxYoRirMOT",
				"Z_pbkWjpHt2jnh1wIel2Q",
				"wn2u0XYeZLoO2lx3_EEKG",
				"utWEnkHNdmRq-ErZe34TV"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "9giQq9iqFjp57A91lWwG9",
					"type": "arrow"
				}
			],
			"updated": 1700563029732,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 1024,
			"versionNonce": 1125237854,
			"isDeleted": false,
			"id": "SYQyRuoPioPtejdwGpZ1E",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 3887.372625222121,
			"y": 296.7298801222732,
			"strokeColor": "#ced4da",
			"backgroundColor": "#ced4da",
			"width": 14.038447272896667,
			"height": 1.2404679615420366,
			"seed": 1900607102,
			"groupIds": [
				"2kKSuI-hZGZIxYoRirMOT",
				"Z_pbkWjpHt2jnh1wIel2Q",
				"wn2u0XYeZLoO2lx3_EEKG",
				"utWEnkHNdmRq-ErZe34TV"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029732,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 1101,
			"versionNonce": 52541570,
			"isDeleted": false,
			"id": "bA1CL5MPwnNLM6oBUbryU",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 3887.33619410447,
			"y": 297.99654840265197,
			"strokeColor": "#ced4da",
			"backgroundColor": "#ced4da",
			"width": 1.1384422672753027,
			"height": 3.392454355884956,
			"seed": 1679914686,
			"groupIds": [
				"2kKSuI-hZGZIxYoRirMOT",
				"Z_pbkWjpHt2jnh1wIel2Q",
				"wn2u0XYeZLoO2lx3_EEKG",
				"utWEnkHNdmRq-ErZe34TV"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029732,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 1132,
			"versionNonce": 55937182,
			"isDeleted": false,
			"id": "QVjJV3g4GWSZ66F3E1NTO",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 3890.987446270376,
			"y": 298.01553751613795,
			"strokeColor": "#ced4da",
			"backgroundColor": "#ced4da",
			"width": 0.9397482321261998,
			"height": 3.3544761289134053,
			"seed": 545255166,
			"groupIds": [
				"2kKSuI-hZGZIxYoRirMOT",
				"Z_pbkWjpHt2jnh1wIel2Q",
				"wn2u0XYeZLoO2lx3_EEKG",
				"utWEnkHNdmRq-ErZe34TV"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "3MlhtSeM9o6QkxsKJLTid",
					"type": "arrow"
				}
			],
			"updated": 1700563029732,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 985,
			"versionNonce": 756766786,
			"isDeleted": false,
			"id": "4OpD0YY7vWmEkI7a9hVPw",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 3902.138832968371,
			"y": 296.5215325339047,
			"strokeColor": "#ffffff",
			"backgroundColor": "#ffffff",
			"width": 1.657163138279252,
			"height": 1.657163138279252,
			"seed": 1927634750,
			"groupIds": [
				"2kKSuI-hZGZIxYoRirMOT",
				"Z_pbkWjpHt2jnh1wIel2Q",
				"wn2u0XYeZLoO2lx3_EEKG",
				"utWEnkHNdmRq-ErZe34TV"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "9giQq9iqFjp57A91lWwG9",
					"type": "arrow"
				}
			],
			"updated": 1700563029732,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 929,
			"versionNonce": 1192674526,
			"isDeleted": false,
			"id": "-FNEcXeXpIASTJ8dAulzS",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 4017.114687647224,
			"y": 366.84828244611276,
			"strokeColor": "#ced4da",
			"backgroundColor": "#ced4da",
			"width": 7.653166918459806,
			"height": 7.653166918459806,
			"seed": 1359703522,
			"groupIds": [
				"4IjVlsk-KiFtBmlks8LWG",
				"EPfAXFJwbrwBoQEc9k8q4",
				"ZB5niSsfKMi6XvPONq6ad",
				"utWEnkHNdmRq-ErZe34TV"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029732,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 740,
			"versionNonce": 1850408962,
			"isDeleted": false,
			"id": "OxEScdSGvyGnrgBYMyU9x",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 4007.3135474677483,
			"y": 370.0546319245716,
			"strokeColor": "#ced4da",
			"backgroundColor": "#ced4da",
			"width": 14.038447272896667,
			"height": 1.2404679615420366,
			"seed": 1927766434,
			"groupIds": [
				"4IjVlsk-KiFtBmlks8LWG",
				"EPfAXFJwbrwBoQEc9k8q4",
				"ZB5niSsfKMi6XvPONq6ad",
				"utWEnkHNdmRq-ErZe34TV"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029732,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 817,
			"versionNonce": 803633438,
			"isDeleted": false,
			"id": "oknN_w0d30fAKhDRpab-l",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 4007.2771163500975,
			"y": 371.3213002049504,
			"strokeColor": "#ced4da",
			"backgroundColor": "#ced4da",
			"width": 1.1384422672753027,
			"height": 3.392454355884956,
			"seed": 613342562,
			"groupIds": [
				"4IjVlsk-KiFtBmlks8LWG",
				"EPfAXFJwbrwBoQEc9k8q4",
				"ZB5niSsfKMi6XvPONq6ad",
				"utWEnkHNdmRq-ErZe34TV"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029732,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 849,
			"versionNonce": 45068226,
			"isDeleted": false,
			"id": "RhikoFbqNCG3WzbCY0egH",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 4010.9283685160035,
			"y": 371.34028931843613,
			"strokeColor": "#ced4da",
			"backgroundColor": "#ced4da",
			"width": 0.9397482321261998,
			"height": 3.3544761289134053,
			"seed": 1934680354,
			"groupIds": [
				"4IjVlsk-KiFtBmlks8LWG",
				"EPfAXFJwbrwBoQEc9k8q4",
				"ZB5niSsfKMi6XvPONq6ad",
				"utWEnkHNdmRq-ErZe34TV"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "UWAmt74s4OJ40icN7sy-B",
					"type": "arrow"
				},
				{
					"id": "9giQq9iqFjp57A91lWwG9",
					"type": "arrow"
				}
			],
			"updated": 1700563029732,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 700,
			"versionNonce": 87401822,
			"isDeleted": false,
			"id": "GyyRrpWQSvdyUoZaXOPey",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 4022.0797552139984,
			"y": 369.84628433620287,
			"strokeColor": "#ffffff",
			"backgroundColor": "#ffffff",
			"width": 1.657163138279252,
			"height": 1.657163138279252,
			"seed": 1788636386,
			"groupIds": [
				"4IjVlsk-KiFtBmlks8LWG",
				"EPfAXFJwbrwBoQEc9k8q4",
				"ZB5niSsfKMi6XvPONq6ad",
				"utWEnkHNdmRq-ErZe34TV"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029732,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 1002,
			"versionNonce": 1315465090,
			"isDeleted": false,
			"id": "2y67JEulww_KnB2KEoI2S",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 4017.4215513910653,
			"y": 411.49690809706135,
			"strokeColor": "#d2bab0",
			"backgroundColor": "#d2bab0",
			"width": 7.653166918459806,
			"height": 7.653166918459806,
			"seed": 1882910142,
			"groupIds": [
				"KHw5o5xtmL4rl9QgT6So2",
				"utWEnkHNdmRq-ErZe34TV"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029732,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 813,
			"versionNonce": 2018855326,
			"isDeleted": false,
			"id": "aeajWb54DoIfw4HIeOrSq",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 4007.6204112115897,
			"y": 414.7032575755202,
			"strokeColor": "#d2bab0",
			"backgroundColor": "#d2bab0",
			"width": 14.038447272896667,
			"height": 1.2404679615420366,
			"seed": 2018674174,
			"groupIds": [
				"KHw5o5xtmL4rl9QgT6So2",
				"utWEnkHNdmRq-ErZe34TV"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029732,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 890,
			"versionNonce": 1504978754,
			"isDeleted": false,
			"id": "Y4TUMW7OauMvRhy7PivTn",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 4007.583980093939,
			"y": 415.96992585589896,
			"strokeColor": "#d2bab0",
			"backgroundColor": "#d2bab0",
			"width": 1.1384422672753027,
			"height": 3.392454355884956,
			"seed": 38606398,
			"groupIds": [
				"KHw5o5xtmL4rl9QgT6So2",
				"utWEnkHNdmRq-ErZe34TV"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029732,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 920,
			"versionNonce": 1752589790,
			"isDeleted": false,
			"id": "KK9w5TH1jieh_oJqVKH1K",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 4011.235232259845,
			"y": 415.9889149693847,
			"strokeColor": "#d2bab0",
			"backgroundColor": "#d2bab0",
			"width": 0.9397482321261998,
			"height": 3.3544761289134053,
			"seed": 1191943806,
			"groupIds": [
				"KHw5o5xtmL4rl9QgT6So2",
				"utWEnkHNdmRq-ErZe34TV"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029732,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 836,
			"versionNonce": 1290923778,
			"isDeleted": false,
			"id": "Q1KfmqjHIGIhumUoIncYh",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 4022.38661895784,
			"y": 414.49490998715146,
			"strokeColor": "#ffffff",
			"backgroundColor": "#ffffff",
			"width": 1.657163138279252,
			"height": 1.657163138279252,
			"seed": 995040958,
			"groupIds": [
				"KHw5o5xtmL4rl9QgT6So2",
				"utWEnkHNdmRq-ErZe34TV"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029732,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 1101,
			"versionNonce": 648673822,
			"isDeleted": false,
			"id": "uWLItNzR1eWxgA-Jxry8U",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 4089.7037936274073,
			"y": 447.00538416670287,
			"strokeColor": "#d2bab0",
			"backgroundColor": "#d2bab0",
			"width": 7.653166918459806,
			"height": 7.653166918459806,
			"seed": 539617918,
			"groupIds": [
				"9XkfcUX7uKXHtk9eIhaTf",
				"utWEnkHNdmRq-ErZe34TV"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029732,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 914,
			"versionNonce": 1822473922,
			"isDeleted": false,
			"id": "5Zgmy4E3AXG7HtCL7_PJK",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 4079.9026534479317,
			"y": 450.2117336451617,
			"strokeColor": "#d2bab0",
			"backgroundColor": "#d2bab0",
			"width": 14.038447272896667,
			"height": 1.2404679615420366,
			"seed": 1925442238,
			"groupIds": [
				"9XkfcUX7uKXHtk9eIhaTf",
				"utWEnkHNdmRq-ErZe34TV"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029732,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 989,
			"versionNonce": 971048542,
			"isDeleted": false,
			"id": "j034xgMld89Ot0JqYPxxd",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 4079.866222330281,
			"y": 451.4784019255405,
			"strokeColor": "#d2bab0",
			"backgroundColor": "#d2bab0",
			"width": 1.1384422672753027,
			"height": 3.392454355884956,
			"seed": 447996670,
			"groupIds": [
				"9XkfcUX7uKXHtk9eIhaTf",
				"utWEnkHNdmRq-ErZe34TV"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029732,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 1019,
			"versionNonce": 358585986,
			"isDeleted": false,
			"id": "OLHigsGdL-BBnIIEp0WAC",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 4083.517474496187,
			"y": 451.49739103902624,
			"strokeColor": "#d2bab0",
			"backgroundColor": "#d2bab0",
			"width": 0.9397482321261998,
			"height": 3.3544761289134053,
			"seed": 1786434366,
			"groupIds": [
				"9XkfcUX7uKXHtk9eIhaTf",
				"utWEnkHNdmRq-ErZe34TV"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029732,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 935,
			"versionNonce": 585927326,
			"isDeleted": false,
			"id": "sSjDWraaFLIEe4Ty1VNmm",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 4094.668861194181,
			"y": 450.003386056793,
			"strokeColor": "#ffffff",
			"backgroundColor": "#ffffff",
			"width": 1.657163138279252,
			"height": 1.657163138279252,
			"seed": 1014610814,
			"groupIds": [
				"9XkfcUX7uKXHtk9eIhaTf",
				"utWEnkHNdmRq-ErZe34TV"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029732,
			"link": null,
			"locked": false
		},
		{
			"type": "line",
			"version": 1275,
			"versionNonce": 938309186,
			"isDeleted": false,
			"id": "fP0OsmQywLruNzpXydgBp",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 4078.2184342474384,
			"y": 394.78841466304743,
			"strokeColor": "#343a40",
			"backgroundColor": "#e9ecef",
			"width": 22.14708311172035,
			"height": 24.130454142792942,
			"seed": 1659966114,
			"groupIds": [
				"kdzKLn6iMkV_shkTKw4DQ",
				"utWEnkHNdmRq-ErZe34TV"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029732,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0.1203270473103599,
					24.005320225658252
				],
				[
					22.14708311172035,
					24.111737464531767
				],
				[
					21.88001261937419,
					8.227633470246298
				],
				[
					13.149698259866312,
					8.113729895119095
				],
				[
					13.113013436853755,
					-0.0187166782611744
				],
				[
					0,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 797,
			"versionNonce": 545097438,
			"isDeleted": false,
			"id": "nBr6atQrqra6rSS3Qqfij",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 4091.3756032241135,
			"y": 394.7926800118737,
			"strokeColor": "#343a40",
			"backgroundColor": "#ced4da",
			"width": 8.650828821827663,
			"height": 8.199209701414512,
			"seed": 708472418,
			"groupIds": [
				"kdzKLn6iMkV_shkTKw4DQ",
				"utWEnkHNdmRq-ErZe34TV"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029732,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					8.650828821827663,
					8.199209701414512
				]
			]
		},
		{
			"type": "line",
			"version": 797,
			"versionNonce": 1428774402,
			"isDeleted": false,
			"id": "wWS9m4SLFenSOVLWA0l5k",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 4080.454139366463,
			"y": 398.16632069913294,
			"strokeColor": "#ffffff",
			"backgroundColor": "#e9ecef",
			"width": 8.866049136951656,
			"height": 0.044809929066387116,
			"seed": 1063408162,
			"groupIds": [
				"kdzKLn6iMkV_shkTKw4DQ",
				"utWEnkHNdmRq-ErZe34TV"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029732,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					8.866049136951656,
					-0.044809929066387116
				]
			]
		},
		{
			"type": "line",
			"version": 810,
			"versionNonce": 1931803422,
			"isDeleted": false,
			"id": "YK9G0b_Y967CsccZath7X",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 4080.454139366463,
			"y": 406.4640535991591,
			"strokeColor": "#ffffff",
			"backgroundColor": "#e9ecef",
			"width": 15.561284221290792,
			"height": 0.017371250034547793,
			"seed": 1968684514,
			"groupIds": [
				"kdzKLn6iMkV_shkTKw4DQ",
				"utWEnkHNdmRq-ErZe34TV"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029732,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					15.561284221290792,
					0.017371250034547793
				]
			]
		},
		{
			"type": "line",
			"version": 861,
			"versionNonce": 2048019906,
			"isDeleted": false,
			"id": "xC7tGAhKJmUlBMe3YlqMY",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 4080.454139366463,
			"y": 402.3375921136792,
			"strokeColor": "#ffffff",
			"backgroundColor": "#e9ecef",
			"width": 8.866049136951656,
			"height": 0.044809929066387116,
			"seed": 1764340130,
			"groupIds": [
				"kdzKLn6iMkV_shkTKw4DQ",
				"utWEnkHNdmRq-ErZe34TV"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029732,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					8.866049136951656,
					-0.044809929066387116
				]
			]
		},
		{
			"type": "line",
			"version": 892,
			"versionNonce": 559146846,
			"isDeleted": false,
			"id": "teKf41a5Hd3LtudvLj55W",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 4080.454139366463,
			"y": 410.6078863346735,
			"strokeColor": "#ffffff",
			"backgroundColor": "#e9ecef",
			"width": 15.561284221290792,
			"height": 0.017371250034547793,
			"seed": 1040657762,
			"groupIds": [
				"kdzKLn6iMkV_shkTKw4DQ",
				"utWEnkHNdmRq-ErZe34TV"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029732,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					15.561284221290792,
					0.017371250034547793
				]
			]
		},
		{
			"type": "line",
			"version": 824,
			"versionNonce": 1002915202,
			"isDeleted": false,
			"id": "Z7Osb3Wy0Ds5kduV4lE-r",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 4080.454139366463,
			"y": 414.75171907018796,
			"strokeColor": "#ffffff",
			"backgroundColor": "#e9ecef",
			"width": 15.561284221290792,
			"height": 0.017371250034547793,
			"seed": 1497313570,
			"groupIds": [
				"kdzKLn6iMkV_shkTKw4DQ",
				"utWEnkHNdmRq-ErZe34TV"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029732,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					15.561284221290792,
					0.017371250034547793
				]
			]
		},
		{
			"type": "arrow",
			"version": 621,
			"versionNonce": 995838878,
			"isDeleted": false,
			"id": "3MlhtSeM9o6QkxsKJLTid",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "dashed",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 3897.1364227712716,
			"y": 428.5442853700102,
			"strokeColor": "#e03131",
			"backgroundColor": "transparent",
			"width": 20.101569390749773,
			"height": 115.56315980524488,
			"seed": 1694658366,
			"groupIds": [
				"utWEnkHNdmRq-ErZe34TV"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1700563029732,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": {
				"elementId": "QVjJV3g4GWSZ66F3E1NTO",
				"focus": 21.971447459576808,
				"gap": 13.952592889854486
			},
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					-20.101569390749773,
					-115.56315980524488
				]
			]
		},
		{
			"type": "text",
			"version": 401,
			"versionNonce": 864503106,
			"isDeleted": false,
			"id": "t8TH9sxv",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "dashed",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 3744.10117491492,
			"y": 268.69561992158185,
			"strokeColor": "#e03131",
			"backgroundColor": "transparent",
			"width": 87.81619262695312,
			"height": 20.81001394517042,
			"seed": 1825260350,
			"groupIds": [
				"utWEnkHNdmRq-ErZe34TV"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029732,
			"link": null,
			"locked": false,
			"fontSize": 8.67083914382101,
			"fontFamily": 3,
			"text": "정보를 탈취해도\n풀 수 있는 방법이 없음",
			"rawText": "정보를 탈취해도\n풀 수 있는 방법이 없음",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "정보를 탈취해도\n풀 수 있는 방법이 없음",
			"lineHeight": 1.2,
			"baseline": 18
		},
		{
			"type": "rectangle",
			"version": 82,
			"versionNonce": 527181790,
			"isDeleted": false,
			"id": "jKUGOqJNH2p73wRVZMGRm",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2303.9182142183768,
			"y": 2075.411419779357,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 485.1926611249464,
			"height": 474.0550117776065,
			"seed": 1172671263,
			"groupIds": [
				"4jIcvXtYIarNdY2dpD-YV"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029732,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 82,
			"versionNonce": 2058439938,
			"isDeleted": false,
			"id": "QCBkVQBQ",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2310.9037868441897,
			"y": 2038.8816954919207,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 175.78125,
			"height": 24,
			"seed": 568344191,
			"groupIds": [
				"4jIcvXtYIarNdY2dpD-YV"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029732,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 3,
			"text": "Namespace - PID",
			"rawText": "Namespace - PID",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Namespace - PID",
			"lineHeight": 1.2,
			"baseline": 20
		},
		{
			"type": "rectangle",
			"version": 127,
			"versionNonce": 1033337886,
			"isDeleted": false,
			"id": "toSgvRwOcQ8bem8v5T8gu",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2324.9634540991387,
			"y": 2098.7972777994805,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#a5d8ff",
			"width": 77,
			"height": 34,
			"seed": 1689412127,
			"groupIds": [
				"4jIcvXtYIarNdY2dpD-YV"
			],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"type": "text",
					"id": "ZIZH9zBm"
				}
			],
			"updated": 1700563029732,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 117,
			"versionNonce": 650403010,
			"isDeleted": false,
			"id": "ZIZH9zBm",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2334.1665790991387,
			"y": 2103.7972777994805,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#a5d8ff",
			"width": 58.59375,
			"height": 24,
			"seed": 1873220383,
			"groupIds": [
				"4jIcvXtYIarNdY2dpD-YV"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029732,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 3,
			"text": "PID 1",
			"rawText": "PID 1",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "toSgvRwOcQ8bem8v5T8gu",
			"originalText": "PID 1",
			"lineHeight": 1.2,
			"baseline": 20
		},
		{
			"type": "rectangle",
			"version": 434,
			"versionNonce": 1540245598,
			"isDeleted": false,
			"id": "8ygMfbYoENPH8PULgGT6N",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2501.810488288136,
			"y": 2247.8421053170114,
			"strokeColor": "#2f9e44",
			"backgroundColor": "transparent",
			"width": 255.7501512862824,
			"height": 218.4590462318438,
			"seed": 768355551,
			"groupIds": [
				"4jIcvXtYIarNdY2dpD-YV"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029732,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 237,
			"versionNonce": 1163883650,
			"isDeleted": false,
			"id": "eJn9s7LN",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2496.978010353798,
			"y": 2206.218539365693,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 269.53125,
			"height": 24,
			"seed": 1989228799,
			"groupIds": [
				"4jIcvXtYIarNdY2dpD-YV"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029732,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 3,
			"text": "Child System(Container)",
			"rawText": "Child System(Container)",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Child System(Container)",
			"lineHeight": 1.2,
			"baseline": 20
		},
		{
			"type": "rectangle",
			"version": 482,
			"versionNonce": 1507953822,
			"isDeleted": false,
			"id": "KVuYINJy7iEl3CH8A26Z7",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2518.4489562990852,
			"y": 2267.9314359657965,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#b2f2bb",
			"width": 77,
			"height": 34,
			"seed": 1461698847,
			"groupIds": [
				"4jIcvXtYIarNdY2dpD-YV"
			],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"type": "text",
					"id": "WGcnm42n"
				}
			],
			"updated": 1700563029732,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 243,
			"versionNonce": 1480692802,
			"isDeleted": false,
			"id": "WGcnm42n",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2527.6520812990852,
			"y": 2272.9314359657965,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#a5d8ff",
			"width": 58.59375,
			"height": 24,
			"seed": 283657535,
			"groupIds": [
				"4jIcvXtYIarNdY2dpD-YV"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029732,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 3,
			"text": "PID 1",
			"rawText": "PID 1",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "KVuYINJy7iEl3CH8A26Z7",
			"originalText": "PID 1",
			"lineHeight": 1.2,
			"baseline": 20
		},
		{
			"type": "rectangle",
			"version": 559,
			"versionNonce": 1971472606,
			"isDeleted": false,
			"id": "xZCDI0DrJa6VvGR0UgWyL",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2555.000210191612,
			"y": 2325.6419306597013,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#b2f2bb",
			"width": 77,
			"height": 34,
			"seed": 409772767,
			"groupIds": [
				"4jIcvXtYIarNdY2dpD-YV"
			],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"type": "text",
					"id": "z2AC2gNt"
				}
			],
			"updated": 1700563029733,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 322,
			"versionNonce": 1363786754,
			"isDeleted": false,
			"id": "z2AC2gNt",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2564.203335191612,
			"y": 2330.6419306597013,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#a5d8ff",
			"width": 58.59375,
			"height": 24,
			"seed": 1639116543,
			"groupIds": [
				"4jIcvXtYIarNdY2dpD-YV"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029733,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 3,
			"text": "PID 2",
			"rawText": "PID 2",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "xZCDI0DrJa6VvGR0UgWyL",
			"originalText": "PID 2",
			"lineHeight": 1.2,
			"baseline": 20
		},
		{
			"type": "rectangle",
			"version": 169,
			"versionNonce": 239172894,
			"isDeleted": false,
			"id": "7Xc4g5Pvyzf3xrfrxCRyr",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2359.5171382079825,
			"y": 2152.510446577987,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#a5d8ff",
			"width": 77,
			"height": 34,
			"seed": 2137826129,
			"groupIds": [
				"4jIcvXtYIarNdY2dpD-YV"
			],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"type": "text",
					"id": "d9JIARnv"
				}
			],
			"updated": 1700563029733,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 159,
			"versionNonce": 242674626,
			"isDeleted": false,
			"id": "d9JIARnv",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2368.7202632079825,
			"y": 2157.510446577987,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#a5d8ff",
			"width": 58.59375,
			"height": 24,
			"seed": 1098780977,
			"groupIds": [
				"4jIcvXtYIarNdY2dpD-YV"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029733,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 3,
			"text": "PID 1",
			"rawText": "PID 1",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "7Xc4g5Pvyzf3xrfrxCRyr",
			"originalText": "PID 1",
			"lineHeight": 1.2,
			"baseline": 20
		},
		{
			"type": "rectangle",
			"version": 197,
			"versionNonce": 1771055454,
			"isDeleted": false,
			"id": "kYDiXlYHw-x5OnHqQfOnT",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2359.5171382079825,
			"y": 2210.2209412718917,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#a5d8ff",
			"width": 77,
			"height": 34,
			"seed": 331519199,
			"groupIds": [
				"4jIcvXtYIarNdY2dpD-YV"
			],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"type": "text",
					"id": "W3n5wfvx"
				}
			],
			"updated": 1700563029733,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 187,
			"versionNonce": 1441276802,
			"isDeleted": false,
			"id": "W3n5wfvx",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2368.7202632079825,
			"y": 2215.2209412718917,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#a5d8ff",
			"width": 58.59375,
			"height": 24,
			"seed": 561684735,
			"groupIds": [
				"4jIcvXtYIarNdY2dpD-YV"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029733,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 3,
			"text": "PID 1",
			"rawText": "PID 1",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "kYDiXlYHw-x5OnHqQfOnT",
			"originalText": "PID 1",
			"lineHeight": 1.2,
			"baseline": 20
		},
		{
			"type": "rectangle",
			"version": 173,
			"versionNonce": 1992248734,
			"isDeleted": false,
			"id": "kLppXzykh5Y2w92CzCBYl",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2359.2742771585704,
			"y": 2267.9314359657965,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#a5d8ff",
			"width": 77,
			"height": 34,
			"seed": 2006571455,
			"groupIds": [
				"4jIcvXtYIarNdY2dpD-YV"
			],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"type": "text",
					"id": "PZxEE8Im"
				}
			],
			"updated": 1700563029733,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 163,
			"versionNonce": 1373397826,
			"isDeleted": false,
			"id": "PZxEE8Im",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2368.4774021585704,
			"y": 2272.9314359657965,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#a5d8ff",
			"width": 58.59375,
			"height": 24,
			"seed": 399919583,
			"groupIds": [
				"4jIcvXtYIarNdY2dpD-YV"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029733,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 3,
			"text": "PID 1",
			"rawText": "PID 1",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "kLppXzykh5Y2w92CzCBYl",
			"originalText": "PID 1",
			"lineHeight": 1.2,
			"baseline": 20
		},
		{
			"type": "rectangle",
			"version": 172,
			"versionNonce": 318761438,
			"isDeleted": false,
			"id": "bp1TAUhJNDhznzwJaU2Yg",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2359.5171382079825,
			"y": 2325.6419306597013,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#a5d8ff",
			"width": 77,
			"height": 34,
			"seed": 434570289,
			"groupIds": [
				"4jIcvXtYIarNdY2dpD-YV"
			],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"type": "text",
					"id": "LzmDu4ZG"
				}
			],
			"updated": 1700563029733,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 162,
			"versionNonce": 213035778,
			"isDeleted": false,
			"id": "LzmDu4ZG",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2368.7202632079825,
			"y": 2330.6419306597013,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#a5d8ff",
			"width": 58.59375,
			"height": 24,
			"seed": 1673090577,
			"groupIds": [
				"4jIcvXtYIarNdY2dpD-YV"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029733,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 3,
			"text": "PID 1",
			"rawText": "PID 1",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "bp1TAUhJNDhznzwJaU2Yg",
			"originalText": "PID 1",
			"lineHeight": 1.2,
			"baseline": 20
		},
		{
			"type": "line",
			"version": 124,
			"versionNonce": 1298333214,
			"isDeleted": false,
			"id": "5bS6QFWx5dnLixq-b8dUb",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "dashed",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2449.9129595841114,
			"y": 2285.2185992785267,
			"strokeColor": "#2f9e44",
			"backgroundColor": "#b2f2bb",
			"width": 67.34906905068101,
			"height": 0.07609066888790039,
			"seed": 432481087,
			"groupIds": [
				"4jIcvXtYIarNdY2dpD-YV"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1700563029733,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					67.34906905068101,
					0.07609066888790039
				]
			]
		},
		{
			"type": "line",
			"version": 195,
			"versionNonce": 1827273410,
			"isDeleted": false,
			"id": "Q18Ec_qcei4GQ3IS_ZInP",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "dashed",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2452.02403831495,
			"y": 2342.3237311591147,
			"strokeColor": "#2f9e44",
			"backgroundColor": "#b2f2bb",
			"width": 92.64506757040135,
			"height": 0.2719910974205959,
			"seed": 30990815,
			"groupIds": [
				"4jIcvXtYIarNdY2dpD-YV"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1700563029733,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					92.64506757040135,
					0.2719910974205959
				]
			]
		},
		{
			"type": "rectangle",
			"version": 227,
			"versionNonce": 718899806,
			"isDeleted": false,
			"id": "kaTheWbDYy6fY6zBNb5EH",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 3865.6189875791097,
			"y": 875.8727309506858,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 70.05729166666652,
			"height": 45.33333333333335,
			"seed": 1115353535,
			"groupIds": [
				"lLBsyUxoK9mR6aYhofQFU",
				"Ul7Jo29TyoD7umPCwvOq8"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029733,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 121,
			"versionNonce": 824267394,
			"isDeleted": false,
			"id": "yqNPtYgCTE0AJ08kYjLUW",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 3872.424935123247,
			"y": 926.0764550406303,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 56.44539657839141,
			"height": 9.124543814987305,
			"seed": 429479615,
			"groupIds": [
				"lLBsyUxoK9mR6aYhofQFU",
				"Ul7Jo29TyoD7umPCwvOq8"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029733,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 108,
			"versionNonce": 1781829278,
			"isDeleted": false,
			"id": "FxClnGxeXRINdjVuz8TJl",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 3870.623637154331,
			"y": 880.2934945403938,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 60.047992516223076,
			"height": 36.73570126647803,
			"seed": 1582611935,
			"groupIds": [
				"lLBsyUxoK9mR6aYhofQFU",
				"Ul7Jo29TyoD7umPCwvOq8"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029733,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 341,
			"versionNonce": 1813492290,
			"isDeleted": false,
			"id": "_UGWi7k_UDuujGAw6-JXA",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 4062.376479154238,
			"y": 866.4471387330402,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 48.359375,
			"height": 71.77604166666676,
			"seed": 1654197361,
			"groupIds": [
				"sirbcg7Gp4MfMikb2jrTk",
				"Ul7Jo29TyoD7umPCwvOq8"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029733,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 160,
			"versionNonce": 1210387166,
			"isDeleted": false,
			"id": "rq4DPZoQIv8z5onAWMetr",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 4099.1623988308875,
			"y": 878.5186287906988,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 2.05311410880131,
			"height": 2.05311410880131,
			"seed": 809065599,
			"groupIds": [
				"sirbcg7Gp4MfMikb2jrTk",
				"Ul7Jo29TyoD7umPCwvOq8"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029733,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 88,
			"versionNonce": 11278850,
			"isDeleted": false,
			"id": "Se75yoHUlC2NLkZ9kWQEX",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 4071.896820368787,
			"y": 890.2033455191785,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 29.31869257090193,
			"height": 5.175235714639712,
			"seed": 1156439263,
			"groupIds": [
				"sirbcg7Gp4MfMikb2jrTk",
				"Ul7Jo29TyoD7umPCwvOq8"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029733,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 137,
			"versionNonce": 1128005406,
			"isDeleted": false,
			"id": "uO525diH0fH6T73BM7T-E",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 4071.896820368787,
			"y": 899.9257363117931,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 29.31869257090193,
			"height": 5.175235714639712,
			"seed": 678322833,
			"groupIds": [
				"sirbcg7Gp4MfMikb2jrTk",
				"Ul7Jo29TyoD7umPCwvOq8"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029733,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 109,
			"versionNonce": 501057986,
			"isDeleted": false,
			"id": "ZwtAgHDvbYkLJRfMO8JTm",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 3900.634966924296,
			"y": 945.5694807427572,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 0.24097847124949112,
			"height": 158.80164941200314,
			"seed": 1693421439,
			"groupIds": [
				"Ul7Jo29TyoD7umPCwvOq8"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029733,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 254,
			"versionNonce": 1609198430,
			"isDeleted": false,
			"id": "OvRHJBYHxzZefaMhz8JrY",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 4086.5435001660917,
			"y": 945.5694807427572,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 0.06798812914166767,
			"height": 154.50058816644926,
			"seed": 589906385,
			"groupIds": [
				"Ul7Jo29TyoD7umPCwvOq8"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029733,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 83,
			"versionNonce": 986382722,
			"isDeleted": false,
			"id": "-5rH3pd-ji-F3_yTmBNaQ",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 3901.324976470439,
			"y": 994.557699398582,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 183.73316805874947,
			"height": 0.1174528900853602,
			"seed": 1706852127,
			"groupIds": [
				"Ul7Jo29TyoD7umPCwvOq8"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029733,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 118,
			"versionNonce": 1820413854,
			"isDeleted": false,
			"id": "eM4J_ZwD7U9O0mhVgwoKP",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 3902.181691668708,
			"y": 1076.4373332739488,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 183.73316805874947,
			"height": 0.1174528900853602,
			"seed": 30753567,
			"groupIds": [
				"Ul7Jo29TyoD7umPCwvOq8"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029733,
			"link": null,
			"locked": false
		},
		{
			"type": "arrow",
			"version": 351,
			"versionNonce": 313753922,
			"isDeleted": false,
			"id": "JfDN7s40NLdwN32DkOZyp",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 4087.0962429892256,
			"y": 1009.9191382933616,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 30.070654090649896,
			"height": 50.35429736614617,
			"seed": 303878097,
			"groupIds": [
				"Ul7Jo29TyoD7umPCwvOq8"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029733,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					29.955430146328126,
					0.19304583961195476
				],
				[
					30.070654090649896,
					50.10866912049039
				],
				[
					0.8133715708727323,
					50.35429736614617
				]
			]
		},
		{
			"type": "text",
			"version": 48,
			"versionNonce": 1160883166,
			"isDeleted": false,
			"id": "FQLONdx6",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 3962.1401695902155,
			"y": 965.7224591100282,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 58.59375,
			"height": 24,
			"seed": 1182054193,
			"groupIds": [
				"Ul7Jo29TyoD7umPCwvOq8"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029733,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 3,
			"text": "GET /",
			"rawText": "GET /",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "GET /",
			"lineHeight": 1.2,
			"baseline": 20
		},
		{
			"type": "text",
			"version": 114,
			"versionNonce": 552995074,
			"isDeleted": false,
			"id": "uEz633SZ",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 4125.869927700267,
			"y": 1009.8810839706443,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 128.90625,
			"height": 48,
			"seed": 1851667039,
			"groupIds": [
				"Ul7Jo29TyoD7umPCwvOq8"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029733,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 3,
			"text": "요청 처리\n/index.html",
			"rawText": "요청 처리\n/index.html",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "요청 처리\n/index.html",
			"lineHeight": 1.2,
			"baseline": 44
		},
		{
			"type": "text",
			"version": 284,
			"versionNonce": 403472414,
			"isDeleted": false,
			"id": "BTIA36tE",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 3928.9814186788926,
			"y": 1023.5382215894938,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 128.90625,
			"height": 48,
			"seed": 594106097,
			"groupIds": [
				"Ul7Jo29TyoD7umPCwvOq8"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029733,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 3,
			"text": "200 OK\n/index.html",
			"rawText": "200 OK\n/index.html",
			"textAlign": "center",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "200 OK\n/index.html",
			"lineHeight": 1.2,
			"baseline": 44
		},
		{
			"type": "line",
			"version": 116,
			"versionNonce": 487692482,
			"isDeleted": false,
			"id": "LB6UpoLMTTqvc5ddleYE-",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 4070.39487693536,
			"y": 980.0224949518494,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 16.104751117170508,
			"height": 28.00081470680334,
			"seed": 1256243647,
			"groupIds": [
				"Ul7Jo29TyoD7umPCwvOq8"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029733,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					16.104751117170508,
					14.027660649139648
				],
				[
					0.8506921598213921,
					28.00081470680334
				]
			]
		},
		{
			"type": "line",
			"version": 248,
			"versionNonce": 688049246,
			"isDeleted": false,
			"id": "tBaikmbSOyrChV1o9iVIg",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 3.148244570703751,
			"x": 3900.878404113071,
			"y": 1062.218434897627,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 16.104751117170508,
			"height": 28.00081470680334,
			"seed": 1034660895,
			"groupIds": [
				"Ul7Jo29TyoD7umPCwvOq8"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029733,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					16.104751117170508,
					14.027660649139648
				],
				[
					0.8506921598213921,
					28.00081470680334
				]
			]
		},
		{
			"type": "rectangle",
			"version": 341,
			"versionNonce": 1990537346,
			"isDeleted": false,
			"id": "QVEWD7HKkr3Simi6eQd1I",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 3868.469785211487,
			"y": 1301.1834793412197,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 70.05729166666652,
			"height": 45.33333333333335,
			"seed": 410690161,
			"groupIds": [
				"ZRlZTYJPQkFtPgdrfJbLB",
				"oN13jXW4IOBOXG_cPqeLH"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029733,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 235,
			"versionNonce": 367366302,
			"isDeleted": false,
			"id": "0qoChAtoPL6w54ANO8EQV",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 3875.2757327556237,
			"y": 1351.3872034311644,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 56.44539657839141,
			"height": 9.124543814987305,
			"seed": 46083153,
			"groupIds": [
				"ZRlZTYJPQkFtPgdrfJbLB",
				"oN13jXW4IOBOXG_cPqeLH"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029733,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 222,
			"versionNonce": 1366282306,
			"isDeleted": false,
			"id": "ObxqMurDgmgAaBg559s18",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 3873.474434786708,
			"y": 1305.6042429309277,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 60.047992516223076,
			"height": 36.73570126647803,
			"seed": 731347505,
			"groupIds": [
				"ZRlZTYJPQkFtPgdrfJbLB",
				"oN13jXW4IOBOXG_cPqeLH"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029733,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 455,
			"versionNonce": 442879198,
			"isDeleted": false,
			"id": "EcszCXL0h8we1CgS0uLFh",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 4065.227276786615,
			"y": 1291.7578871235742,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 48.359375,
			"height": 71.77604166666676,
			"seed": 334171153,
			"groupIds": [
				"-kfUUMDDOtj9b3UvBpeEC",
				"oN13jXW4IOBOXG_cPqeLH"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029733,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 274,
			"versionNonce": 22050818,
			"isDeleted": false,
			"id": "K-D_Smq0wOZnmsLw6c-Fq",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 4102.013196463264,
			"y": 1303.8293771812328,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 2.05311410880131,
			"height": 2.05311410880131,
			"seed": 867262961,
			"groupIds": [
				"-kfUUMDDOtj9b3UvBpeEC",
				"oN13jXW4IOBOXG_cPqeLH"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029733,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 202,
			"versionNonce": 1410629918,
			"isDeleted": false,
			"id": "sSlcVDzrRyB-sCYVXUTGA",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 4074.7476180011645,
			"y": 1315.5140939097123,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 29.31869257090193,
			"height": 5.175235714639712,
			"seed": 401734609,
			"groupIds": [
				"-kfUUMDDOtj9b3UvBpeEC",
				"oN13jXW4IOBOXG_cPqeLH"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029733,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 251,
			"versionNonce": 105260994,
			"isDeleted": false,
			"id": "7FJLZ5UjZMPuIqz5FIpla",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 4074.7476180011645,
			"y": 1325.2364847023273,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 29.31869257090193,
			"height": 5.175235714639712,
			"seed": 1086609841,
			"groupIds": [
				"-kfUUMDDOtj9b3UvBpeEC",
				"oN13jXW4IOBOXG_cPqeLH"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029733,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 334,
			"versionNonce": 107130206,
			"isDeleted": false,
			"id": "tzdTMN8rihElj2gEWXuf4",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 3902.8129280723106,
			"y": 1370.8802291332913,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 0.0001270004117941425,
			"height": 400.9442415210076,
			"seed": 1062206353,
			"groupIds": [
				"oN13jXW4IOBOXG_cPqeLH"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029733,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 620,
			"versionNonce": 141549442,
			"isDeleted": false,
			"id": "zFzZm8lBTFNRJ2GeEQhXV",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 4090.409935596999,
			"y": 1370.8802291332913,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 0.07672385858040781,
			"height": 398.3862345367139,
			"seed": 332161393,
			"groupIds": [
				"oN13jXW4IOBOXG_cPqeLH"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029733,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 179,
			"versionNonce": 1587630494,
			"isDeleted": false,
			"id": "lRQbB1H0",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 3971.8726626056496,
			"y": 1397.447529807346,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 46.875,
			"height": 19.2,
			"seed": 78356721,
			"groupIds": [
				"oN13jXW4IOBOXG_cPqeLH"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029733,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 3,
			"text": "GET /",
			"rawText": "GET /",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "GET /",
			"lineHeight": 1.2,
			"baseline": 15
		},
		{
			"type": "text",
			"version": 365,
			"versionNonce": 1410113346,
			"isDeleted": false,
			"id": "twAdz7ux",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 4128.832267437057,
			"y": 1447.4116071554158,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 169.1195068359375,
			"height": 30.43418299923346,
			"seed": 1833720529,
			"groupIds": [
				"oN13jXW4IOBOXG_cPqeLH"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029733,
			"link": null,
			"locked": false,
			"fontSize": 12.680909583013943,
			"fontFamily": 3,
			"text": "요청 전처리\nURL 재작성, 내부 목적지 전환",
			"rawText": "요청 전처리\nURL 재작성, 내부 목적지 전환",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "요청 전처리\nURL 재작성, 내부 목적지 전환",
			"lineHeight": 1.2,
			"baseline": 27
		},
		{
			"type": "text",
			"version": 759,
			"versionNonce": 939617758,
			"isDeleted": false,
			"id": "vrAPh6PF",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 3944.0470138367405,
			"y": 1685.4165428395024,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 103.125,
			"height": 38.4,
			"seed": 1501223089,
			"groupIds": [
				"oN13jXW4IOBOXG_cPqeLH"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029733,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 3,
			"text": "200 OK\n/index.html",
			"rawText": "200 OK\n/index.html",
			"textAlign": "center",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "200 OK\n/index.html",
			"lineHeight": 1.2,
			"baseline": 34
		},
		{
			"type": "rectangle",
			"version": 200,
			"versionNonce": 1434150658,
			"isDeleted": false,
			"id": "r77CCKVAAFdbuV1WrI0mI",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 3904.175774102817,
			"y": 1419.868447789116,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 183.73316805874947,
			"height": 0.1174528900853602,
			"seed": 1266748241,
			"groupIds": [
				"KTf3XnTZXw5LOKpXKLzj-",
				"oN13jXW4IOBOXG_cPqeLH"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029733,
			"link": null,
			"locked": false
		},
		{
			"type": "line",
			"version": 231,
			"versionNonce": 1603535390,
			"isDeleted": false,
			"id": "tV8dbU6H0noCYMfD7XJTT",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 4073.2456745677373,
			"y": 1405.3332433423834,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 16.104751117170508,
			"height": 28.00081470680334,
			"seed": 450796177,
			"groupIds": [
				"KTf3XnTZXw5LOKpXKLzj-",
				"oN13jXW4IOBOXG_cPqeLH"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029733,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					16.104751117170508,
					14.027660649139648
				],
				[
					0.8506921598213921,
					28.00081470680334
				]
			]
		},
		{
			"type": "rectangle",
			"version": 536,
			"versionNonce": 356202178,
			"isDeleted": false,
			"id": "xOK3olhBIsnSmmCu7E8bv",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 3905.020191074504,
			"y": 1727.266513823142,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 183.73316805874947,
			"height": 0.1174528900853602,
			"seed": 1589999921,
			"groupIds": [
				"gYpDrHOIumE6-EfWSNwli",
				"oN13jXW4IOBOXG_cPqeLH"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029733,
			"link": null,
			"locked": false
		},
		{
			"type": "line",
			"version": 666,
			"versionNonce": 1481248350,
			"isDeleted": false,
			"id": "wAOFffHoG0iqdoT64oM8b",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 3.148244570703751,
			"x": 3903.7169035188676,
			"y": 1713.0476154468204,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 16.104751117170508,
			"height": 28.00081470680334,
			"seed": 1647255665,
			"groupIds": [
				"gYpDrHOIumE6-EfWSNwli",
				"oN13jXW4IOBOXG_cPqeLH"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029733,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					16.104751117170508,
					14.027660649139648
				],
				[
					0.8506921598213921,
					28.00081470680334
				]
			]
		},
		{
			"type": "text",
			"version": 186,
			"versionNonce": 871042690,
			"isDeleted": false,
			"id": "v6s6kUio",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 4033.040264511199,
			"y": 1246.8161886438904,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 125.00497436523438,
			"height": 38.4,
			"seed": 2090307199,
			"groupIds": [
				"oN13jXW4IOBOXG_cPqeLH"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029733,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 3,
			"text": "[웹서버]\n엔진엑스/아파치..",
			"rawText": "[웹서버]\n엔진엑스/아파치..",
			"textAlign": "center",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "[웹서버]\n엔진엑스/아파치..",
			"lineHeight": 1.2,
			"baseline": 34
		},
		{
			"type": "text",
			"version": 187,
			"versionNonce": 519344798,
			"isDeleted": false,
			"id": "tQxh5KfF",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 3825.215992322546,
			"y": 1246.8161886438904,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 159.375,
			"height": 38.4,
			"seed": 2037056479,
			"groupIds": [
				"oN13jXW4IOBOXG_cPqeLH"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029733,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 3,
			"text": "[클라이언트]\nchrome, firefox..",
			"rawText": "[클라이언트]\nchrome, firefox..",
			"textAlign": "center",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "[클라이언트]\nchrome, firefox..",
			"lineHeight": 1.2,
			"baseline": 34
		},
		{
			"type": "rectangle",
			"version": 671,
			"versionNonce": 1716121154,
			"isDeleted": false,
			"id": "H2DJ4ia-5zv3DYwK0oQhz",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 4324.150864357443,
			"y": 1378.1422148905967,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 0.11318959000255167,
			"height": 391.1621673975962,
			"seed": 1943316497,
			"groupIds": [
				"oN13jXW4IOBOXG_cPqeLH"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029733,
			"link": null,
			"locked": false
		},
		{
			"type": "freedraw",
			"version": 1637,
			"versionNonce": 1849986782,
			"isDeleted": false,
			"id": "mXolseS-CM4C0_UdVQBVQ",
			"fillStyle": "solid",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 4320.93534135656,
			"y": 1304.6930872853193,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 100.36161453713959,
			"height": 65.37308211777098,
			"seed": 429431647,
			"groupIds": [
				"oN13jXW4IOBOXG_cPqeLH"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029733,
			"link": null,
			"locked": false,
			"points": [
				[
					-21.605149333426972,
					-2.074931297058254
				],
				[
					-21.751187586292424,
					-2.074931297058254
				],
				[
					-22.187714972574774,
					-2.074931297058254
				],
				[
					-22.624242358857625,
					-1.9240575848412136
				],
				[
					-23.408404281852253,
					-1.9240575848412136
				],
				[
					-24.19256620484687,
					-1.9240575848412136
				],
				[
					-25.12117900839344,
					-2.0765892499397656
				],
				[
					-26.762521980816157,
					-2.0765892499397656
				],
				[
					-28.40386495323838,
					-2.4297332137004477
				],
				[
					-29.332477756784947,
					-2.6518988998222293
				],
				[
					-30.11663967977957,
					-2.6518988998222293
				],
				[
					-30.55316706606192,
					-2.6518988998222293
				],
				[
					-30.98969445234477,
					-2.6518988998222293
				],
				[
					-31.57067271917907,
					-2.6518988998222293
				],
				[
					-33.212015691601295,
					-2.6518988998222293
				],
				[
					-34.85335866402351,
					-1.7963952129653364
				],
				[
					-35.14543516975442,
					-1.7963952129653364
				],
				[
					-35.437511675485325,
					-1.4946477885312555
				],
				[
					-36.22167359847995,
					-1.1232663430739451
				],
				[
					-38.018579057650186,
					0.3191526638359927
				],
				[
					-38.59955732448448,
					0.9226475127041547
				],
				[
					-39.902789994077,
					2.2805109226572577
				],
				[
					-41.06157178311807,
					3.4875006203934498
				],
				[
					-42.22035357215913,
					4.694490318129644
				],
				[
					-42.65688095844148,
					5.147111454780767
				],
				[
					-43.14102951413665,
					6.707245116277511
				],
				[
					-44.36648094035515,
					8.428200207280499
				],
				[
					-46.0887799007789,
					11.861820624878911
				],
				[
					-46.71737933702601,
					13.572827998592826
				],
				[
					-47.519002355472246,
					17.878531631863247
				],
				[
					-47.85711265830196,
					20.697051530422915
				],
				[
					-47.85711265830196,
					23.515571428982593
				],
				[
					-47.85711265830196,
					26.33409132754239
				],
				[
					-47.85711265830196,
					30.638137007931295
				],
				[
					-47.85711265830196,
					34.942182688320074
				],
				[
					-47.85711265830196,
					39.246228368708984
				],
				[
					-47.85711265830196,
					43.55193200197941
				],
				[
					-47.096761320013485,
					45.626031056743074
				],
				[
					-46.087192528465394,
					49.853810904582716
				],
				[
					-45.20143877739011,
					51.92790995934638
				],
				[
					-44.45378641761172,
					55.48919274882066
				],
				[
					-43.906142969366144,
					57.56329180358434
				],
				[
					-43.69502245163727,
					58.52987833350211
				],
				[
					-43.55057157108532,
					59.13337318237028
				],
				[
					-43.26166980998193,
					59.435120606804226
				],
				[
					-43.117218929430486,
					59.435120606804226
				],
				[
					-42.8283171683271,
					59.435120606804226
				],
				[
					-40.84251440382013,
					59.435120606804226
				],
				[
					-40.4091617621648,
					59.435120606804226
				],
				[
					-39.975809120509965,
					59.435120606804226
				],
				[
					-39.831358239958035,
					59.435120606804226
				],
				[
					-39.05037106159093,
					58.9907892345608
				],
				[
					-38.90592018103898,
					58.53485219214665
				],
				[
					-38.76146930048754,
					57.715823468682764
				],
				[
					-38.550348782758164,
					56.382829351952196
				],
				[
					-38.126520374985404,
					55.412926916271395
				],
				[
					-38.126520374985404,
					54.956989873857246
				],
				[
					-38.126520374985404,
					54.3501791192262
				],
				[
					-38.126520374985404,
					53.89424207681218
				],
				[
					-38.126520374985404,
					53.28743132218099
				],
				[
					-38.126520374985404,
					52.46840259871722
				],
				[
					-38.126520374985404,
					51.345968497937875
				],
				[
					-38.272558627850856,
					50.526939774473966
				],
				[
					-38.272558627850856,
					49.92012901984291
				],
				[
					-38.272558627850856,
					49.464191977428776
				],
				[
					-38.272558627850856,
					48.49428954174797
				],
				[
					-38.272558627850856,
					47.52438710606716
				],
				[
					-37.916987229570026,
					46.55448467038621
				],
				[
					-37.70586671184064,
					45.73545594692245
				],
				[
					-37.494746194111265,
					45.068958888557106
				],
				[
					-37.35029531355981,
					44.76389555836
				],
				[
					-37.06139355245644,
					44.45883222816302
				],
				[
					-37.06139355245644,
					44.306300563064475
				],
				[
					-36.77249179135305,
					43.85036352065046
				],
				[
					-35.53592875893797,
					42.12609252388446
				],
				[
					-34.23587083397298,
					40.76325525528669
				],
				[
					-33.946969072869585,
					40.45819192508971
				],
				[
					-32.791362028456035,
					39.24788632159049
				],
				[
					-32.50246026735265,
					38.641075566959444
				],
				[
					-31.121446354386133,
					36.76427290509488
				],
				[
					-30.832544593282744,
					36.15746215046382
				],
				[
					-30.197595667781094,
					34.82446803373327
				],
				[
					-30.197595667781094,
					34.36853099131912
				],
				[
					-29.764243026126262,
					33.9125939489051
				],
				[
					-29.408671627844942,
					33.0935652254412
				],
				[
					-29.119769866741557,
					32.63762818302719
				],
				[
					-28.97531898619011,
					32.332564852830096
				],
				[
					-28.97531898619011,
					32.18003318773154
				],
				[
					-28.97531898619011,
					31.876627810416075
				],
				[
					-28.830868105638167,
					31.573222433100483
				],
				[
					-28.830868105638167,
					31.42069076800194
				],
				[
					-28.830868105638167,
					31.117285390686483
				],
				[
					-28.830868105638167,
					31.26815910290351
				],
				[
					-28.830868105638167,
					31.56990652733746
				],
				[
					-28.976906358503623,
					32.02252766398859
				],
				[
					-29.12294461136908,
					32.32427508842254
				],
				[
					-29.268982864234534,
					32.626022512856615
				],
				[
					-29.268982864234534,
					33.07864364950773
				],
				[
					-29.415021117099986,
					33.38039107394182
				],
				[
					-29.56105936996544,
					33.53126478615872
				],
				[
					-29.56105936996544,
					33.833012210592806
				],
				[
					-29.986475150051714,
					34.49785131607664
				],
				[
					-30.34522129296006,
					35.46443784599443
				],
				[
					-30.683331595789774,
					37.538536900758096
				],
				[
					-31.042077738698616,
					38.505123430675866
				],
				[
					-31.254785628741505,
					39.47170996059379
				],
				[
					-31.254785628741505,
					39.773457385027875
				],
				[
					-31.46749351878489,
					40.58917020272862
				],
				[
					-31.46749351878489,
					40.740043914945645
				],
				[
					-31.178591757681502,
					40.89091762716269
				],
				[
					-29.19278899317453,
					40.89091762716269
				],
				[
					-28.26735093425549,
					40.89091762716269
				],
				[
					-27.630814636439833,
					40.89091762716269
				],
				[
					-27.341912875336444,
					41.19266505159678
				],
				[
					-26.90856023368111,
					41.645286188247766
				],
				[
					-26.486319198222354,
					42.97496439921542
				],
				[
					-26.341868317670908,
					43.941550929133214
				],
				[
					-26.052966556567526,
					44.54504577800124
				],
				[
					-26.052966556567526,
					44.99766691465237
				],
				[
					-26.052966556567526,
					45.81337973235324
				],
				[
					-25.90851567601608,
					46.11512715678731
				],
				[
					-25.90851567601608,
					46.718622005655355
				],
				[
					-25.90851567601608,
					47.5343348233561
				],
				[
					-25.90851567601608,
					47.98695596000722
				],
				[
					-25.90851567601608,
					48.59045080887525
				],
				[
					-25.90851567601608,
					49.04307194552638
				],
				[
					-25.764064795464137,
					49.49569308217736
				],
				[
					-25.764064795464137,
					49.94831421882848
				],
				[
					-25.61961391491269,
					50.09918793104551
				],
				[
					-25.61961391491269,
					51.065774460963304
				],
				[
					-25.61961391491269,
					51.881487278664174
				],
				[
					-25.330712153809305,
					52.334108415315164
				],
				[
					-25.330712153809305,
					52.78672955196629
				],
				[
					-25.330712153809305,
					53.60244236966716
				],
				[
					-25.330712153809305,
					53.7533160818842
				],
				[
					-25.330712153809305,
					54.56902889958495
				],
				[
					-25.330712153809305,
					54.870776324019026
				],
				[
					-25.330712153809305,
					55.323397460670016
				],
				[
					-25.330712153809305,
					55.6251448851041
				],
				[
					-25.330712153809305,
					56.07776602175523
				],
				[
					-25.186261273257358,
					56.228639733972265
				],
				[
					-25.186261273257358,
					56.8321345828403
				],
				[
					-25.04181039270592,
					57.133882007274245
				],
				[
					-25.04181039270592,
					57.58650314392536
				],
				[
					-25.04181039270592,
					58.55308967384328
				],
				[
					-25.04181039270592,
					58.85483709827724
				],
				[
					-25.04181039270592,
					59.307458234928355
				],
				[
					-25.04181039270592,
					59.6092056593623
				],
				[
					-25.04181039270592,
					60.06182679601341
				],
				[
					-25.04181039270592,
					60.21270050823047
				],
				[
					-24.897359512153972,
					60.36357422044751
				],
				[
					-24.75290863160253,
					60.36357422044751
				],
				[
					-24.60845775105059,
					60.36357422044751
				],
				[
					-24.319555989947702,
					60.36357422044751
				],
				[
					-23.88620334829237,
					60.51444793266453
				],
				[
					-23.59730158718898,
					60.51444793266453
				],
				[
					-22.671863528269938,
					60.51444793266453
				],
				[
					-22.238510886615103,
					60.51444793266453
				],
				[
					-21.94960912551172,
					60.51444793266453
				],
				[
					-21.66070736440833,
					60.51444793266453
				],
				[
					-21.371805603304946,
					60.51444793266453
				],
				[
					-20.4463675443859,
					60.51444793266453
				],
				[
					-19.520929485466855,
					60.51444793266453
				],
				[
					-18.027212138224098,
					60.51444793266453
				],
				[
					-17.449408616017326,
					60.51444793266453
				],
				[
					-17.30495773546538,
					60.51444793266453
				],
				[
					-16.87160509381055,
					60.51444793266453
				],
				[
					-16.582703332707162,
					60.51444793266453
				],
				[
					-15.801716154340058,
					60.51444793266453
				],
				[
					-15.020728975972458,
					60.36191626756599
				],
				[
					-14.731827214869073,
					60.058510890250396
				],
				[
					-14.587376334317625,
					59.90597922515185
				],
				[
					-13.86512193155941,
					59.44838422985632
				],
				[
					-13.576220170456022,
					59.14332089965922
				],
				[
					-13.287318409352636,
					58.9907892345608
				],
				[
					-12.998416648249249,
					58.68572590436369
				],
				[
					-12.70951488714586,
					58.38066257416658
				],
				[
					-12.420613126042474,
					58.07559924396962
				],
				[
					-12.420613126042474,
					57.92306757887106
				],
				[
					-12.420613126042474,
					57.61800424867396
				],
				[
					-12.209492608313095,
					56.79897552521019
				],
				[
					-11.785664200540825,
					55.82907308952926
				],
				[
					-11.785664200540825,
					54.85917065384845
				],
				[
					-11.641213319988882,
					53.948954521901804
				],
				[
					-11.430092802259503,
					53.28245746353645
				],
				[
					-11.093569871743306,
					51.56647623117813
				],
				[
					-10.804668110640417,
					51.11053918876399
				],
				[
					-10.804668110640417,
					50.65460214634998
				],
				[
					-10.804668110640417,
					50.19866510393583
				],
				[
					-10.804668110640417,
					49.89360177373885
				],
				[
					-10.660217230088476,
					49.74107010864031
				],
				[
					-10.660217230088476,
					49.4376647313247
				],
				[
					-10.660217230088476,
					49.28513306622616
				],
				[
					-10.660217230088476,
					48.67832231159511
				],
				[
					-10.660217230088476,
					48.373258981397996
				],
				[
					-10.51576634953703,
					47.917321938983996
				],
				[
					-10.51576634953703,
					47.76479027388543
				],
				[
					-10.51576634953703,
					47.61225860878689
				],
				[
					-10.51576634953703,
					47.45972694368833
				],
				[
					-10.371315468985088,
					47.00378990127432
				],
				[
					-10.371315468985088,
					46.698726571077216
				],
				[
					-10.371315468985088,
					45.87969784761344
				],
				[
					-10.226864588433644,
					45.57463451741634
				],
				[
					-10.082413707881699,
					45.57463451741634
				],
				[
					-9.793511946778313,
					45.72550822963339
				],
				[
					-9.504610185674926,
					46.02725565406747
				],
				[
					-9.360159305123481,
					46.02725565406747
				],
				[
					-9.215708424571538,
					46.02725565406747
				],
				[
					-8.782355782916708,
					46.02725565406747
				],
				[
					-8.493454021813319,
					46.1781293662845
				],
				[
					-7.71246684344622,
					46.1781293662845
				],
				[
					-4.013889352397562,
					46.68048908938072
				],
				[
					-2.740816756766245,
					46.68048908938072
				],
				[
					-0.04228382338361669,
					46.68048908938072
				],
				[
					0.7387033549839863,
					46.68048908938072
				],
				[
					1.1720559966388162,
					46.68048908938072
				],
				[
					1.4609577577422055,
					46.68048908938072
				],
				[
					1.8943103993970318,
					46.68048908938072
				],
				[
					3.8801131639040083,
					46.68048908938072
				],
				[
					5.153185759535324,
					46.68048908938072
				],
				[
					5.730989281742094,
					46.68048908938072
				],
				[
					6.164341923397426,
					46.68048908938072
				],
				[
					7.089779982315974,
					46.68048908938072
				],
				[
					9.43909100667332,
					46.68048908938072
				],
				[
					13.485303034433752,
					46.68048908938072
				],
				[
					16.183835967816876,
					46.68048908938072
				],
				[
					16.820372265632532,
					46.45832340325893
				],
				[
					17.25372490728736,
					46.45832340325893
				],
				[
					17.398175787839303,
					46.30579173816039
				],
				[
					17.398175787839303,
					46.456665450377415
				],
				[
					17.252137534973855,
					47.42325198029533
				],
				[
					17.252137534973855,
					47.87587311694632
				],
				[
					17.252137534973855,
					48.691585934647065
				],
				[
					17.106099282108406,
					49.14420707129819
				],
				[
					17.106099282108406,
					49.74770192016634
				],
				[
					16.893391392065013,
					50.71428845008414
				],
				[
					16.893391392065013,
					51.37912755556796
				],
				[
					16.680683502022124,
					52.34571408548575
				],
				[
					16.680683502022124,
					52.79833522213688
				],
				[
					16.680683502022124,
					53.61404803983763
				],
				[
					16.680683502022124,
					53.76492175205465
				],
				[
					16.680683502022124,
					54.21754288870578
				],
				[
					16.680683502022124,
					54.36841660092268
				],
				[
					16.825134382573566,
					54.67016402535676
				],
				[
					17.40293790478034,
					54.67016402535676
				],
				[
					18.328375963699386,
					54.67016402535676
				],
				[
					20.314178728206365,
					55.24215776947621
				],
				[
					20.603080489309747,
					55.24215776947621
				],
				[
					21.03643313096458,
					55.24215776947621
				],
				[
					21.469785772619908,
					55.24215776947621
				],
				[
					21.903138414274743,
					55.24215776947621
				],
				[
					22.480941936481514,
					55.24215776947621
				],
				[
					22.625392817032953,
					55.24215776947621
				],
				[
					22.91429457813684,
					55.08962610437779
				],
				[
					23.347647219791668,
					54.93709443927923
				],
				[
					24.12863439815878,
					54.340231401937125
				],
				[
					24.561987039814106,
					54.18769973683871
				],
				[
					25.198523337629275,
					53.96553405071692
				],
				[
					25.342974218181205,
					53.81300238561837
				],
				[
					25.631875979284594,
					53.50959700830277
				],
				[
					25.77632685983604,
					53.357065343204226
				],
				[
					26.06522862093943,
					53.05200201300724
				],
				[
					26.209679501491358,
					52.74693868281014
				],
				[
					26.498581262594747,
					52.29100164039611
				],
				[
					26.6430321431462,
					51.833406645100474
				],
				[
					26.6430321431462,
					51.0143779216367
				],
				[
					26.6430321431462,
					50.7093145914396
				],
				[
					26.85415266087559,
					49.89028586797585
				],
				[
					26.85415266087559,
					49.28347511334464
				],
				[
					26.85415266087559,
					48.676664358713595
				],
				[
					26.85415266087559,
					48.22072731629958
				],
				[
					26.85415266087559,
					47.76479027388543
				],
				[
					26.85415266087559,
					46.94576155042153
				],
				[
					26.85415266087559,
					46.793229885323115
				],
				[
					26.85415266087559,
					46.18641913069206
				],
				[
					26.85415266087559,
					45.881355800494966
				],
				[
					26.85415266087559,
					44.90979541193251
				],
				[
					26.85415266087559,
					44.09076668846875
				],
				[
					26.85415266087559,
					43.785703358271775
				],
				[
					26.85415266087559,
					42.96667463480787
				],
				[
					26.85415266087559,
					42.14764591134397
				],
				[
					26.85415266087559,
					41.32861718788021
				],
				[
					26.85415266087559,
					41.176085522781655
				],
				[
					26.85415266087559,
					41.0235538576831
				],
				[
					26.85415266087559,
					40.871022192584675
				],
				[
					26.85415266087559,
					40.56761681526909
				],
				[
					26.998603541427535,
					40.2642114379535
				],
				[
					27.209724059156898,
					39.597714379588155
				],
				[
					27.643076700811726,
					39.14177733717414
				],
				[
					27.931978461915115,
					38.68584029476012
				],
				[
					28.557403153534203,
					36.9715170152832
				],
				[
					28.98123156130697,
					36.001614579602254
				],
				[
					29.828888376852014,
					34.6686204628717
				],
				[
					30.65273460769039,
					31.104021767634386
				],
				[
					31.663890771552488,
					28.282185963311683
				],
				[
					32.96077395188996,
					24.05109020970903
				],
				[
					33.50841740013503,
					21.973675249182342
				],
				[
					33.93224580790781,
					20.640681132451782
				],
				[
					33.93224580790781,
					19.67077869677084
				],
				[
					34.14336632563718,
					18.700876261090034
				],
				[
					34.14336632563718,
					18.24493921867602
				],
				[
					34.14336632563718,
					17.275036782995084
				],
				[
					34.14336632563718,
					16.30513434731428
				],
				[
					34.14336632563718,
					15.335231911633473
				],
				[
					34.14336632563718,
					13.257816951106651
				],
				[
					34.14336632563718,
					11.543493671629841
				],
				[
					34.14336632563718,
					10.573591235948905
				],
				[
					33.930658435593806,
					9.603688800268099
				],
				[
					33.71795054555091,
					8.63378636458729
				],
				[
					33.23380198985574,
					6.252966026745009
				],
				[
					32.662347956904014,
					5.2830635910642005
				],
				[
					32.51630970403857,
					4.3131611553832645
				],
				[
					32.224233198307665,
					3.85722411296925
				],
				[
					31.932156692576747,
					3.552160782772147
				],
				[
					31.64008018684585,
					3.2470974525751717
				],
				[
					31.34800368111494,
					2.7911604101610274
				],
				[
					31.20196542824948,
					2.638628745062476
				],
				[
					31.055927175384525,
					2.335223367747013
				],
				[
					30.909888922519073,
					2.1826917026484614
				],
				[
					30.763850669653614,
					1.8776283724513565
				],
				[
					30.471774163922703,
					1.7250967073529342
				],
				[
					30.325735911057258,
					1.5725650422543818
				],
				[
					30.033659405326347,
					1.116627999840238
				],
				[
					29.887621152460888,
					0.9640963347416851
				],
				[
					29.741582899595436,
					0.8115646696432639
				],
				[
					29.595544646729984,
					0.6590330045447119
				],
				[
					29.303468140999072,
					0.3539696743476075
				],
				[
					29.157429888133613,
					0.20143800924905486
				],
				[
					29.01139163526817,
					0.04890634415063344
				],
				[
					28.865353382402724,
					-0.10362532094791843
				],
				[
					28.57486424898581,
					-0.10362532094791843
				],
				[
					28.428825996120374,
					-0.10362532094791843
				],
				[
					28.573276876671812,
					-0.10362532094791843
				],
				[
					28.8621786377752,
					-0.25615698604647086
				],
				[
					29.00662951832713,
					-0.40868865114502295
				],
				[
					29.295531279430534,
					-0.40868865114502295
				],
				[
					30.220969338349065,
					-0.40868865114502295
				],
				[
					31.494041933980384,
					-0.40868865114502295
				],
				[
					33.479844698487874,
					-0.40868865114502295
				],
				[
					35.46564746299484,
					-0.40868865114502295
				],
				[
					38.453082157480836,
					-0.40868865114502295
				],
				[
					39.726154753112155,
					-0.40868865114502295
				],
				[
					41.71195751761963,
					-0.40868865114502295
				],
				[
					43.35012574541433,
					-0.40868865114502295
				],
				[
					44.275563804333366,
					-0.40868865114502295
				],
				[
					44.56446556543675,
					-0.40868865114502295
				],
				[
					44.997818207091605,
					-0.40868865114502295
				],
				[
					45.77880538545871,
					-0.40868865114502295
				],
				[
					46.70424344437775,
					-0.40868865114502295
				],
				[
					48.342411672172446,
					-0.40868865114502295
				],
				[
					49.20911695548259,
					-0.40868865114502295
				],
				[
					49.99010413385021,
					-0.40868865114502295
				],
				[
					50.134555014401634,
					-0.40868865114502295
				],
				[
					50.27900589495359,
					-0.40868865114502295
				],
				[
					50.567907656056974,
					-0.40868865114502295
				],
				[
					50.71235853660842,
					-0.40868865114502295
				],
				[
					51.0012602977118,
					-0.40868865114502295
				],
				[
					51.782247476078915,
					-0.40868865114502295
				],
				[
					52.36005099828568,
					-0.40868865114502295
				],
				[
					52.50450187883763,
					-0.40868865114502295
				],
				[
					52.35846362597216,
					-0.2578149389279826
				],
				[
					52.212425373106726,
					-0.2578149389279826
				],
				[
					51.77589798682388,
					-0.2578149389279826
				],
				[
					51.33937060054152,
					-0.2578149389279826
				],
				[
					50.41075779699495,
					-0.2578149389279826
				],
				[
					49.62659587400034,
					-0.2578149389279826
				],
				[
					48.69798307045377,
					-0.2578149389279826
				],
				[
					47.05664009803155,
					-0.2578149389279826
				],
				[
					45.78039275777271,
					-0.2578149389279826
				],
				[
					45.199414490938416,
					-0.10694122671094208
				],
				[
					44.90892535752152,
					-0.10694122671094208
				],
				[
					44.61684885179059,
					-0.10694122671094208
				],
				[
					44.180321465507745,
					0.04393248550609807
				],
				[
					43.888244959776834,
					0.04393248550609807
				],
				[
					43.25012128964769,
					0.04393248550609807
				],
				[
					42.959632156230775,
					0.04393248550609807
				],
				[
					42.66914302281337,
					0.19480619772313923
				],
				[
					42.52310476994793,
					0.34567990994004916
				],
				[
					42.231028264217024,
					0.34567990994004916
				],
				[
					41.44686634122241,
					0.34567990994004916
				],
				[
					41.1547898354915,
					0.34567990994004916
				],
				[
					40.71826244920914,
					0.34567990994004916
				],
				[
					39.934100526213996,
					0.34567990994004916
				],
				[
					39.64202402048311,
					0.34567990994004916
				],
				[
					39.20549663420075,
					0.34567990994004916
				],
				[
					38.478480114501,
					0.34567990994004916
				],
				[
					37.549867310954454,
					0.34567990994004916
				],
				[
					36.62125450740838,
					0.34567990994004916
				],
				[
					35.69264170386182,
					0.34567990994004916
				],
				[
					35.256114317578955,
					0.34567990994004916
				],
				[
					34.67513605074516,
					0.34567990994004916
				],
				[
					34.238608664462305,
					0.34567990994004916
				],
				[
					33.9465321587314,
					0.34567990994004916
				],
				[
					33.80049390586594,
					0.34567990994004916
				],
				[
					33.363966519583606,
					0.34567990994004916
				],
				[
					33.21792826671814,
					0.34567990994004916
				],
				[
					33.07189001385269,
					0.4965536221570894
				],
				[
					32.78140088043579,
					0.4965536221570894
				],
				[
					31.85120070457522,
					0.4965536221570894
				],
				[
					31.559124198844316,
					0.4965536221570894
				],
				[
					30.77496227584969,
					0.7170613553973597
				],
				[
					30.48447314243279,
					0.7170613553973597
				],
				[
					29.846349472303125,
					0.7170613553973597
				],
				[
					29.554272966572213,
					0.7170613553973597
				],
				[
					29.263783833155316,
					0.7170613553973597
				],
				[
					28.973294699737913,
					0.7170613553973597
				],
				[
					28.82725644687296,
					0.7170613553973597
				],
				[
					28.1891327767433,
					0.7170613553973597
				],
				[
					27.75260539046095,
					0.41365597808189736
				],
				[
					27.46052888473004,
					0.26112431298334515
				],
				[
					27.0240014984472,
					-0.043939017213759035
				],
				[
					26.58747411216484,
					-0.043939017213759035
				],
				[
					26.29539760643393,
					-0.19647068231231135
				],
				[
					26.14935935356847,
					-0.34900234741086356
				],
				[
					26.00332110070302,
					-0.34900234741086356
				],
				[
					25.711244594972108,
					-0.34900234741086356
				],
				[
					25.274717208689765,
					-0.5015340125092853
				],
				[
					24.346104405143194,
					-0.7236996986310669
				],
				[
					23.7651261383089,
					-0.8762313637296189
				],
				[
					23.32859875202655,
					-1.1796367410452113
				],
				[
					23.038109618609653,
					-1.1796367410452113
				],
				[
					22.747620485192265,
					-1.3321684061436334
				],
				[
					22.3110930989099,
					-1.3321684061436334
				],
				[
					21.874565712627053,
					-1.3321684061436334
				],
				[
					21.090403789632425,
					-1.5543340922654147
				],
				[
					20.944365536766973,
					-1.5543340922654147
				],
				[
					20.653876403350072,
					-1.5543340922654147
				],
				[
					20.36338726993268,
					-1.7068657573639667
				],
				[
					20.072898136515782,
					-1.859397422462519
				],
				[
					19.636370750232928,
					-2.011929087561071
				],
				[
					16.934663072222786,
					-2.011929087561071
				],
				[
					14.945685563088283,
					-2.2340947736828527
				],
				[
					13.304342590665566,
					-2.739770402542087
				],
				[
					12.374142414805487,
					-2.739770402542087
				],
				[
					11.937615028523133,
					-2.739770402542087
				],
				[
					11.64553852279223,
					-2.739770402542087
				],
				[
					11.064560255957936,
					-3.0431757798576786
				],
				[
					9.788312915699098,
					-3.0431757798576786
				],
				[
					7.08660523768895,
					-3.396319743618361
				],
				[
					5.4452622652662335,
					-3.7494637073790433
				],
				[
					4.661100342271608,
					-3.7494637073790433
				],
				[
					3.38485300201277,
					-3.971629393500824
				],
				[
					2.1086056617539377,
					-3.971629393500824
				],
				[
					1.3244437387593138,
					-3.971629393500824
				],
				[
					0.8879163524769602,
					-3.971629393500824
				],
				[
					0.7418780996115064,
					-3.971629393500824
				],
				[
					-0.04228382338361669,
					-3.971629393500824
				],
				[
					-0.4788112096659667,
					-3.971629393500824
				],
				[
					-1.0597894765002618,
					-3.971629393500824
				],
				[
					-1.8439513994948857,
					-3.971629393500824
				],
				[
					-3.3408434913656633,
					-3.971629393500824
				],
				[
					-4.982186463787885,
					-3.971629393500824
				],
				[
					-9.107767107236334,
					-3.971629393500824
				],
				[
					-12.520617581809127,
					-3.971629393500824
				],
				[
					-14.873103350793496,
					-3.971629393500824
				],
				[
					-15.309630737075846,
					-3.971629393500824
				],
				[
					-15.455668989941302,
					-3.971629393500824
				],
				[
					-15.601707242806754,
					-3.971629393500824
				],
				[
					-15.892196376224152,
					-3.971629393500824
				],
				[
					-16.182685509641047,
					-3.971629393500824
				],
				[
					-16.328723762506502,
					-3.971629393500824
				],
				[
					-16.765251148788856,
					-3.971629393500824
				],
				[
					-16.911289401654308,
					-3.971629393500824
				],
				[
					-17.05732765451976,
					-3.971629393500824
				],
				[
					-17.34781678793716,
					-3.8207556812837846
				],
				[
					-17.639893293668067,
					-3.8207556812837846
				],
				[
					-18.07642067995042,
					-3.519008256849703
				],
				[
					-18.222458932815876,
					-3.519008256849703
				],
				[
					-18.51294806623277,
					-3.368134544632663
				],
				[
					-19.8638019052381,
					-3.016648533753493
				],
				[
					-20.792414708784662,
					-2.796140800513223
				],
				[
					-21.228942095067012,
					-2.3435196638622315
				],
				[
					-21.374980347932464,
					-2.3435196638622315
				],
				[
					-21.52101860079792,
					-2.3435196638622315
				],
				[
					-21.81150773421532,
					-2.1926459516451913
				],
				[
					-21.957545987080273,
					-2.041772239428151
				],
				[
					-22.24803512049767,
					-1.74002481499407
				],
				[
					-22.103584239945725,
					-1.5891511027771599
				],
				[
					-21.95913335939428,
					-1.7416827678755817
				],
				[
					-21.81468247884284,
					-1.8942144329741337
				],
				[
					-21.52578071773945,
					-2.0467460980726857
				],
				[
					-21.381329837187508,
					-2.199277763171238
				],
				[
					-20.600342658820402,
					-2.573975114391441
				],
				[
					-20.311440897717016,
					-2.8790384445885455
				],
				[
					-20.02253913661363,
					-3.031570109687098
				],
				[
					-19.878088256061687,
					-3.33497548700269
				],
				[
					-19.589186494958803,
					-3.4875071521011125
				],
				[
					-19.15583385330347,
					-3.6400388171996645
				],
				[
					-19.011382972752024,
					-3.6400388171996645
				],
				[
					-18.86693209220008,
					-3.7925704822982165
				],
				[
					-18.28912856999331,
					-4.095975859613678
				],
				[
					-18.144677689441863,
					-4.248507524712231
				],
				[
					-17.711325047787035,
					-4.401039189810783
				],
				[
					-17.422423286683646,
					-4.553570854909335
				],
				[
					-17.277972406131703,
					-4.553570854909335
				],
				[
					-17.133521525580257,
					-4.706102520007887
				],
				[
					-16.989070645028317,
					-4.858634185106439
				],
				[
					-16.84461976447687,
					-4.858634185106439
				],
				[
					-16.700168883924928,
					-4.858634185106439
				],
				[
					-16.2668162422701,
					-4.858634185106439
				],
				[
					-16.122365361718153,
					-4.858634185106439
				],
				[
					-15.54456183951188,
					-4.858634185106439
				],
				[
					-15.400110958959937,
					-4.858634185106439
				],
				[
					-14.966758317305105,
					-4.707760472889398
				],
				[
					-14.388954795098332,
					-4.556886760672358
				],
				[
					-12.403152030591361,
					-4.2054007497931885
				],
				[
					-11.477713971672314,
					-3.7627273304311366
				],
				[
					-11.188812210568926,
					-3.611853618214096
				],
				[
					-10.89991044946554,
					-3.460979905997056
				],
				[
					-10.611008688362153,
					-3.3101061937800154
				],
				[
					-10.466557807810709,
					-3.159232481562974
				],
				[
					-10.177656046707321,
					-2.857485057129024
				],
				[
					-10.033205166155378,
					-2.706611344911984
				],
				[
					-9.744303405051992,
					-2.4048639204779034
				],
				[
					-9.599852524500548,
					-2.103116496043822
				],
				[
					-9.455401643948605,
					-1.1365299661260386
				],
				[
					-9.166499882845219,
					-0.8347825416919575
				],
				[
					-8.87759812174183,
					0.2826777004428662
				],
				[
					-8.87759812174183,
					0.43355141265990693
				],
				[
					-8.444245480086998,
					0.8861725493108983
				],
				[
					-8.233124962357621,
					2.0036327914458525
				],
				[
					-8.088674081806177,
					2.4562539280968427
				],
				[
					-7.944223201254234,
					3.422840458014757
				],
				[
					-7.944223201254234,
					4.238553275715502
				],
				[
					-7.944223201254234,
					5.798686937212507
				],
				[
					-7.520394793481964,
					6.7652734671302905
				],
				[
					-7.520394793481964,
					7.731859997048073
				],
				[
					-7.520394793481964,
					9.29199365854508
				],
				[
					-7.520394793481964,
					10.107706476245822
				],
				[
					-7.520394793481964,
					11.818713849959735
				],
				[
					-7.520394793481964,
					12.634426667660609
				],
				[
					-7.520394793481964,
					13.751886909795434
				],
				[
					-7.520394793481964,
					14.355381758663466
				],
				[
					-7.520394793481964,
					14.657129183097545
				],
				[
					-7.520394793481964,
					15.41149774418262
				],
				[
					-7.520394793481964,
					16.22721056188349
				],
				[
					-7.520394793481964,
					17.04292337958423
				],
				[
					-7.520394793481964,
					17.344670804018314
				],
				[
					-7.520394793481964,
					17.79729194066944
				],
				[
					-7.520394793481964,
					17.948165652886477
				],
				[
					-7.666433046347417,
					18.40078678953747
				],
				[
					-7.666433046347417,
					18.551660501754508
				],
				[
					-7.666433046347417,
					18.85340792618859
				],
				[
					-7.8124712992123735,
					19.15515535062254
				],
				[
					-7.8124712992123735,
					19.30602906283958
				],
				[
					-7.9585095520783256,
					19.60777648727366
				],
				[
					-7.9585095520783256,
					19.758650199490702
				],
				[
					-8.10454780494328,
					20.06039762392478
				],
				[
					-8.250586057808734,
					20.211271336141692
				],
				[
					-8.39662431067419,
					20.362145048358727
				],
				[
					-8.609332200717578,
					21.026984153842566
				],
				[
					-8.609332200717578,
					21.177857866059608
				],
				[
					-8.75537045358303,
					21.328731578276642
				],
				[
					-8.75537045358303,
					21.630479002710594
				],
				[
					-8.901408706448485,
					21.932226427144677
				],
				[
					-9.04744695931394,
					22.083100139361715
				],
				[
					-9.193485212179393,
					22.23397385157876
				],
				[
					-9.339523465044849,
					22.535721276012836
				],
				[
					-9.4855617179103,
					22.68659498822975
				],
				[
					-9.631599970775257,
					22.837468700446788
				],
				[
					-9.777638223640711,
					22.837468700446788
				],
				[
					-9.923676476506163,
					22.684937035348362
				],
				[
					-10.069714729371617,
					22.381531658032774
				],
				[
					-10.215752982237072,
					22.228999992934227
				],
				[
					-10.50782948796798,
					21.923936662737116
				],
				[
					-10.50782948796798,
					21.771404997638566
				],
				[
					-10.653867740833434,
					21.467999620323102
				],
				[
					-10.799905993698886,
					21.315467955224555
				],
				[
					-10.945944246564341,
					21.012062577908964
				],
				[
					-11.238020752295249,
					20.85953091281054
				],
				[
					-11.384059005160703,
					20.70699924771199
				],
				[
					-11.530097258026156,
					20.55446758261344
				],
				[
					-11.67613551089161,
					20.40193591751488
				],
				[
					-11.822173763757064,
					20.24940425241633
				],
				[
					-11.968212016622518,
					20.09687258731778
				],
				[
					-12.258701150039416,
					19.944340922219354
				],
				[
					-12.549190283456314,
					19.944340922219354
				],
				[
					-12.695228536322267,
					19.944340922219354
				],
				[
					-12.985717669739165,
					19.944340922219354
				],
				[
					-13.131755922604619,
					20.246088346653305
				],
				[
					-13.422245056021517,
					20.547835771087392
				],
				[
					-13.634952946064907,
					21.36354858878826
				],
				[
					-13.780991198930359,
					21.967043437656294
				],
				[
					-13.780991198930359,
					22.117917149873332
				],
				[
					-13.780991198930359,
					22.93362996757407
				],
				[
					-13.993699088973251,
					23.900216497491986
				],
				[
					-13.993699088973251,
					24.71592931519286
				],
				[
					-13.993699088973251,
					25.01767673962681
				],
				[
					-13.993699088973251,
					25.470297876277932
				],
				[
					-14.285775594704157,
					25.922919012928922
				],
				[
					-14.285775594704157,
					26.587758118412758
				],
				[
					-14.285775594704157,
					26.889505542846837
				],
				[
					-14.431813847569611,
					27.493000391714872
				],
				[
					-14.431813847569611,
					27.945621528365994
				],
				[
					-14.577852100435065,
					29.06308177050081
				],
				[
					-14.577852100435065,
					29.213955482717846
				],
				[
					-14.577852100435065,
					30.029668300418734
				],
				[
					-14.577852100435065,
					31.14712854255356
				],
				[
					-14.577852100435065,
					31.599749679204535
				],
				[
					-14.577852100435065,
					32.566336209122454
				],
				[
					-14.577852100435065,
					32.868083633556544
				],
				[
					-14.577852100435065,
					33.68379645125729
				],
				[
					-14.577852100435065,
					34.49950926895815
				],
				[
					-14.577852100435065,
					34.801256693392105
				],
				[
					-14.577852100435065,
					35.404751542260264
				],
				[
					-14.577852100435065,
					36.008246391128296
				],
				[
					-14.577852100435065,
					36.15912010334534
				],
				[
					-14.577852100435065,
					36.76261495221337
				],
				[
					-14.577852100435065,
					36.91348866443041
				],
				[
					-14.577852100435065,
					37.064362376647445
				],
				[
					-14.577852100435065,
					36.911830711548895
				],
				[
					-14.577852100435065,
					36.75929904645035
				],
				[
					-14.577852100435065,
					36.152488291819296
				],
				[
					-14.577852100435065,
					35.33345956835552
				],
				[
					-14.241329169918867,
					33.466604623780036
				],
				[
					-14.096878289367423,
					33.01066758136601
				],
				[
					-14.096878289367423,
					32.554730538951866
				],
				[
					-13.952427408815481,
					31.58482810327107
				],
				[
					-13.952427408815481,
					30.614925667590256
				],
				[
					-13.807976528264037,
					29.645023231909327
				],
				[
					-13.596856010534658,
					28.825994508445426
				],
				[
					-13.596856010534658,
					27.856092072764625
				],
				[
					-12.922222777188752,
					26.29264250550472
				],
				[
					-12.922222777188752,
					26.140110840406177
				],
				[
					-12.777771896637306,
					25.8350475102092
				],
				[
					-12.777771896637306,
					25.682515845110647
				],
				[
					-12.633321016085363,
					25.37911046779505
				],
				[
					-12.633321016085363,
					25.075705090479588
				],
				[
					-12.633321016085363,
					24.619768048065442
				],
				[
					-12.48887013553392,
					24.012957293434386
				],
				[
					-12.48887013553392,
					23.860425628335843
				],
				[
					-12.199968374430533,
					23.557020251020383
				],
				[
					-12.199968374430533,
					23.40448858592182
				],
				[
					-12.055517493879089,
					23.101083208606234
				],
				[
					-11.911066613327145,
					22.645146166192085
				],
				[
					-11.766615732775701,
					22.341740788876624
				],
				[
					-11.766615732775701,
					22.038335411561036
				],
				[
					-11.477713971672314,
					21.734930034245572
				],
				[
					-11.333263091120372,
					21.582398369147025
				],
				[
					-11.188812210568926,
					21.42986670404847
				],
				[
					-11.044361330016983,
					21.126461326732876
				],
				[
					-10.89991044946554,
					20.973929661634326
				],
				[
					-10.755459568913597,
					20.973929661634326
				],
				[
					-10.611008688362153,
					20.82139799653577
				],
				[
					-10.466557807810709,
					20.82139799653577
				],
				[
					-10.177656046707321,
					20.66886633143735
				],
				[
					-10.033205166155378,
					20.66886633143735
				],
				[
					-9.888754285603934,
					20.66886633143735
				],
				[
					-9.744303405051992,
					20.66886633143735
				],
				[
					-9.31095076339716,
					20.66886633143735
				],
				[
					-9.022049002293773,
					20.66886633143735
				],
				[
					-8.588696360638941,
					20.66886633143735
				],
				[
					-8.299794599535055,
					20.66886633143735
				],
				[
					-8.010892838432166,
					20.819740043654388
				],
				[
					-7.721991077328781,
					21.12148746808834
				],
				[
					-7.577540196776837,
					21.272361180305378
				],
				[
					-6.941003898961181,
					21.492868913545657
				],
				[
					-6.796553018409736,
					21.64374262576269
				],
				[
					-6.796553018409736,
					21.79461633797973
				],
				[
					-6.652102137857793,
					22.096363762413812
				],
				[
					-6.50765125730635,
					22.398111186847764
				],
				[
					-6.50765125730635,
					22.69985861128184
				],
				[
					-6.3632003767544045,
					23.15247974793284
				],
				[
					-6.218749496202963,
					23.45422717236691
				],
				[
					-6.218749496202963,
					24.269939990067783
				],
				[
					-6.218749496202963,
					24.571687414501874
				],
				[
					-6.218749496202963,
					25.024308551152856
				],
				[
					-6.218749496202963,
					25.326055975586936
				],
				[
					-6.218749496202963,
					25.778677112237933
				],
				[
					-6.218749496202963,
					25.929550824454967
				],
				[
					-6.218749496202963,
					26.231298248889058
				],
				[
					-6.218749496202963,
					26.53304567332313
				],
				[
					-6.364787749068415,
					26.83479309775708
				],
				[
					-6.702898051898126,
					28.244053047036918
				],
				[
					-6.848936304763577,
					28.84754789590508
				],
				[
					-7.139425438180477,
					29.3001690325562
				],
				[
					-7.28546369104593,
					29.451042744773247
				],
				[
					-7.28546369104593,
					29.75279016920719
				],
				[
					-7.431501943911385,
					30.054537593641275
				],
				[
					-7.577540196776837,
					30.205411305858313
				],
				[
					-7.577540196776837,
					30.356285018075223
				],
				[
					-7.723578449642291,
					30.658032442509306
				],
				[
					-7.869616702507747,
					30.808906154726348
				],
				[
					-8.0156549553732,
					30.959779866943386
				],
				[
					-8.306144088790099,
					31.110653579160427
				],
				[
					-8.598220594521006,
					31.41240100359451
				],
				[
					-8.74425884738646,
					31.41240100359451
				],
				[
					-9.180786233669311,
					31.563274715811417
				],
				[
					-9.326824486534763,
					31.71414842802846
				],
				[
					-9.472862739400219,
					31.71414842802846
				],
				[
					-9.90939012568257,
					32.015895852462535
				],
				[
					-10.055428378548024,
					32.015895852462535
				],
				[
					-10.345917511964922,
					32.16676956467958
				],
				[
					-10.636406645382317,
					32.16676956467958
				],
				[
					-10.782444898247773,
					32.16676956467958
				],
				[
					-11.07452140397868,
					32.16676956467958
				],
				[
					-11.511048790261032,
					32.31764327689648
				],
				[
					-11.657087043126486,
					32.31764327689648
				],
				[
					-11.803125295991942,
					32.31764327689648
				],
				[
					-12.093614429408838,
					32.31764327689648
				],
				[
					-12.239652682274292,
					32.31764327689648
				],
				[
					-12.385690935139746,
					32.31764327689648
				],
				[
					-12.531729188005201,
					32.31764327689648
				],
				[
					-12.387278307453755,
					32.014237899581026
				],
				[
					-12.242827426901814,
					32.014237899581026
				],
				[
					-12.09837654635037,
					31.861706234482476
				],
				[
					-11.809474785246982,
					31.70917456938392
				],
				[
					-11.520573024143594,
					31.70917456938392
				],
				[
					-11.376122143591651,
					31.556642904285496
				],
				[
					-11.087220382488264,
					31.404111239186946
				],
				[
					-10.942769501936821,
					31.251579574088396
				],
				[
					-10.798318621385377,
					31.251579574088396
				],
				[
					-10.50941686028199,
					31.09904790898984
				],
				[
					-10.076064218626659,
					30.946516243891296
				],
				[
					-9.931613338075215,
					30.946516243891296
				],
				[
					-9.642711576971829,
					30.79398457879274
				],
				[
					-9.35380981586844,
					30.490579201477274
				],
				[
					-9.209358935316498,
					30.338047536378724
				],
				[
					-8.92045717421361,
					30.18551587128017
				],
				[
					-8.776006293661666,
					30.032984206181748
				],
				[
					-8.487104532558279,
					29.880452541083194
				],
				[
					-8.342653652006836,
					29.72792087598465
				],
				[
					-8.198202771454893,
					29.575389210886097
				],
				[
					-8.053751890903449,
					29.422857545787547
				],
				[
					-7.909301010351506,
					29.270325880688993
				],
				[
					-7.620399249248117,
					29.11779421559044
				],
				[
					-7.475948368696676,
					28.965262550492014
				],
				[
					-7.331497488144731,
					28.812730885393464
				],
				[
					-7.187046607593286,
					28.812730885393464
				],
				[
					-7.042595727041844,
					28.66019922029491
				],
				[
					-6.898144846489902,
					28.507667555196363
				],
				[
					-6.898144846489902,
					28.355135890097934
				],
				[
					-6.753693965938455,
					28.20260422499939
				],
				[
					-6.46479220483507,
					27.89919884768379
				],
				[
					-6.320341324283124,
					27.59413551748669
				],
				[
					-6.175890443731681,
					27.290730140171227
				],
				[
					-6.03143956317974,
					27.138198475072674
				],
				[
					-5.742537802076353,
					26.531387720441618
				],
				[
					-5.598086921524907,
					26.37885605534307
				],
				[
					-5.453636040972962,
					25.772045300711884
				],
				[
					-5.242515523244084,
					24.953016577248114
				],
				[
					-4.9536137621402,
					24.649611199932654
				],
				[
					-4.809162881588754,
					24.193674157518505
				],
				[
					-4.809162881588754,
					24.041142492419954
				],
				[
					-4.809162881588754,
					23.585205450005947
				],
				[
					-4.66471200103731,
					23.28014211980884
				],
				[
					-4.66471200103731,
					23.127610454710286
				],
				[
					-4.520261120485368,
					22.671673412296276
				],
				[
					-4.520261120485368,
					22.368268034980684
				],
				[
					-4.30914060275599,
					21.701770976615336
				],
				[
					-4.164689722204542,
					21.549239311516786
				],
				[
					-4.020238841652603,
					21.09330226910277
				],
				[
					-3.8757879611011585,
					20.63736522668876
				],
				[
					-3.7313370805492143,
					20.02889651917606
				],
				[
					-3.7313370805492143,
					19.572959476762048
				],
				[
					-3.5868861999977684,
					19.117022434348033
				],
				[
					-3.4424353194458286,
					18.811959104150926
				],
				[
					-3.4424353194458286,
					18.50689577395383
				],
				[
					-3.4424353194458286,
					18.05095873153981
				],
				[
					-3.4424353194458286,
					17.898427066441254
				],
				[
					-3.29798443889438,
					17.593363736244154
				],
				[
					-3.29798443889438,
					17.137426693830136
				],
				[
					-3.29798443889438,
					16.984895028731586
				],
				[
					-3.29798443889438,
					16.832363363633032
				],
				[
					-3.153533558342441,
					16.073020943903426
				],
				[
					-3.153533558342441,
					15.769615566587968
				],
				[
					-3.153533558342441,
					15.617083901489414
				],
				[
					-3.153533558342441,
					15.46455223639086
				],
				[
					-3.153533558342441,
					15.312020571292313
				],
				[
					-3.153533558342441,
					14.856083528878164
				],
				[
					-3.153533558342441,
					14.703551863779744
				],
				[
					-3.153533558342441,
					14.551020198681188
				],
				[
					-3.153533558342441,
					14.247614821365598
				],
				[
					-3.153533558342441,
					14.39848853358264
				],
				[
					-3.153533558342441,
					14.700235958016721
				],
				[
					-3.153533558342441,
					15.00198338245067
				],
				[
					-3.153533558342441,
					16.119443624585625
				],
				[
					-3.512279701251285,
					16.935156442286495
				],
				[
					-3.512279701251285,
					17.90174297220428
				],
				[
					-3.8503900040809897,
					19.461876633701156
				],
				[
					-3.8503900040809897,
					20.126715739184995
				],
				[
					-3.8503900040809897,
					20.57933687583598
				],
				[
					-3.9964282569464444,
					21.031958012487106
				],
				[
					-3.9964282569464444,
					21.63545286135513
				],
				[
					-3.9964282569464444,
					21.937200285789213
				],
				[
					-3.9964282569464444,
					22.389821422440335
				],
				[
					-3.9964282569464444,
					22.842442559091324
				],
				[
					-3.9964282569464444,
					23.295063695742314
				],
				[
					-3.9964282569464444,
					23.44593740795936
				],
				[
					-3.9964282569464444,
					23.596811120176397
				],
				[
					-3.9964282569464444,
					24.261650225660226
				],
				[
					-3.9964282569464444,
					24.41252393787727
				],
				[
					-3.9964282569464444,
					24.56339765009431
				],
				[
					-3.9964282569464444,
					25.0160187867453
				],
				[
					-3.9964282569464444,
					25.317766211179382
				],
				[
					-3.9964282569464444,
					25.770387347830372
				],
				[
					-3.9964282569464444,
					25.92126106004741
				],
				[
					-3.9964282569464444,
					26.52475590891557
				],
				[
					-3.9964282569464444,
					26.826503333349656
				],
				[
					-3.9964282569464444,
					27.279124470000642
				],
				[
					-3.9964282569464444,
					27.580871894434726
				],
				[
					-3.9964282569464444,
					28.033493031085715
				],
				[
					-3.9964282569464444,
					28.3352404555198
				],
				[
					-3.9964282569464444,
					28.787861592170923
				],
				[
					-3.9964282569464444,
					28.93873530438796
				],
				[
					-3.9964282569464444,
					29.08960901660487
				],
				[
					-3.9964282569464444,
					29.39135644103895
				],
				[
					-3.9964282569464444,
					29.542230153255993
				],
				[
					-3.9964282569464444,
					29.693103865473034
				],
				[
					-3.9964282569464444,
					29.843977577689945
				],
				[
					-3.9964282569464444,
					30.14572500212402
				],
				[
					-3.9964282569464444,
					30.296598714341055
				],
				[
					-3.9964282569464444,
					30.447472426558107
				],
				[
					-3.9964282569464444,
					30.598346138775145
				],
				[
					-3.9964282569464444,
					30.90009356320923
				],
				[
					-3.9964282569464444,
					30.747561898110675
				],
				[
					-3.9964282569464444,
					30.442498567913567
				],
				[
					-3.9964282569464444,
					30.139093190597983
				],
				[
					-3.707526495843056,
					29.169190754917164
				],
				[
					-3.707526495843056,
					28.502693696551958
				],
				[
					-3.5630756152911145,
					28.19763036635485
				],
				[
					-3.418624734739671,
					27.58916165884215
				],
				[
					-3.418624734739671,
					27.43662999374374
				],
				[
					-3.274173854188228,
					26.82816128623117
				],
				[
					-2.9852720930848395,
					26.22135053159998
				],
				[
					-2.9852720930848395,
					25.765413489185967
				],
				[
					-2.840821212532898,
					25.309476446771818
				],
				[
					-2.840821212532898,
					25.156944781673396
				],
				[
					-2.840821212532898,
					24.701007739259257
				],
				[
					-2.696370331981452,
					24.5484760741607
				],
				[
					-2.696370331981452,
					24.39594440906215
				],
				[
					-2.340798933700132,
					23.576915685598383
				],
				[
					-2.0518971725967443,
					23.271852355401286
				],
				[
					-1.9074462920453001,
					22.96678902520431
				],
				[
					-1.7629954114933586,
					22.81425736010576
				],
				[
					-1.329642769838527,
					22.3566623648101
				],
				[
					-1.185191889287081,
					22.20413069971155
				],
				[
					-0.7518392476317501,
					21.748193657297534
				],
				[
					-0.6073883670803042,
					21.595661992198988
				],
				[
					-0.3184866059769167,
					21.44313032710056
				],
				[
					-0.17403572542497692,
					21.139724949784963
				],
				[
					0.11486603567841058,
					20.987193284686416
				],
				[
					0.5482186773332423,
					20.834661619587862
				],
				[
					0.9815713189880704,
					20.529598289390762
				],
				[
					1.2704730800914597,
					20.529598289390762
				],
				[
					1.5593748411948471,
					20.529598289390762
				],
				[
					1.9927274828501798,
					20.529598289390762
				],
				[
					2.2816292439530663,
					20.529598289390762
				],
				[
					2.4260801245050114,
					20.680472001607804
				],
				[
					2.859432766159843,
					20.83134571382484
				],
				[
					3.003883646711781,
					20.83134571382484
				],
				[
					3.1483345272632253,
					20.982219426041876
				],
				[
					3.2927854078151704,
					21.133093138258925
				],
				[
					3.726138049470002,
					21.434840562692997
				],
				[
					3.8705889300219454,
					21.585714274910046
				],
				[
					4.0150398105733895,
					21.887461699343987
				],
				[
					4.303941571676777,
					22.189209123778074
				],
				[
					4.448392452228717,
					22.340082835995112
				],
				[
					4.592843332780159,
					22.79270397264611
				],
				[
					4.592843332780159,
					22.943577684863147
				],
				[
					4.737294213331607,
					23.245325109297223
				],
				[
					4.737294213331607,
					23.547072533731306
				],
				[
					4.737294213331607,
					23.84881995816539
				],
				[
					4.737294213331607,
					24.301441094816376
				],
				[
					4.737294213331607,
					24.603188519250462
				],
				[
					4.737294213331607,
					25.206683368118487
				],
				[
					4.737294213331607,
					25.659304504769608
				],
				[
					4.737294213331607,
					25.96105192920356
				],
				[
					4.737294213331607,
					26.11192564142061
				],
				[
					4.737294213331607,
					26.776764746904433
				],
				[
					4.737294213331607,
					27.078512171338385
				],
				[
					4.737294213331607,
					27.380259595772475
				],
				[
					4.737294213331607,
					27.531133307989506
				],
				[
					4.737294213331607,
					27.682007020206544
				],
				[
					4.737294213331607,
					28.13462815685767
				],
				[
					4.737294213331607,
					28.285501869074707
				],
				[
					4.737294213331607,
					28.58724929350866
				],
				[
					4.737294213331607,
					28.888996717942742
				],
				[
					4.737294213331607,
					29.03987043015978
				],
				[
					4.737294213331607,
					29.19074414237669
				],
				[
					4.737294213331607,
					29.34161785459373
				],
				[
					4.737294213331607,
					29.794238991244853
				],
				[
					4.737294213331607,
					30.09598641567893
				],
				[
					4.5912559604666505,
					30.548607552329926
				],
				[
					4.5912559604666505,
					30.699481264546964
				],
				[
					4.5912559604666505,
					30.85035497676401
				],
				[
					4.5912559604666505,
					31.152102401198086
				],
				[
					4.5912559604666505,
					31.302976113414992
				],
				[
					4.5912559604666505,
					31.453849825632034
				],
				[
					4.5912559604666505,
					31.60472353784909
				],
				[
					4.5912559604666505,
					31.90647096228315
				],
				[
					4.5912559604666505,
					32.0573446745002
				],
				[
					4.5912559604666505,
					31.904813009401643
				],
				[
					4.5912559604666505,
					31.752281344303093
				],
				[
					4.735706841018093,
					31.29634430188907
				],
				[
					4.8801577215695335,
					30.838749306593424
				],
				[
					5.024608602121484,
					30.686217641495006
				],
				[
					5.169059482672921,
					30.22862264619935
				],
				[
					5.380180000402309,
					29.562125587833997
				],
				[
					5.524630880954252,
					29.40959392273545
				],
				[
					5.669081761505694,
					28.590565199271683
				],
				[
					5.813532642057634,
					28.43803353417313
				],
				[
					5.957983522609084,
					28.285501869074707
				],
				[
					6.102434403161023,
					27.829564826660572
				],
				[
					6.246885283712466,
					27.677033161562008
				],
				[
					6.535787044815855,
					27.221096119147997
				],
				[
					6.680237925367294,
					27.068564454049447
				],
				[
					6.969139686470683,
					26.612627411635433
				],
				[
					7.258041447574072,
					26.156690369221284
				],
				[
					7.402492328126016,
					26.00415870412274
				],
				[
					7.613612845855393,
					25.18512998065897
				],
				[
					7.613612845855393,
					24.36610125719507
				],
				[
					7.758063726406835,
					24.06269587987961
				],
				[
					8.046965487510224,
					23.606758837465463
				],
				[
					8.046965487510224,
					23.30335346014988
				],
				[
					8.191416368062171,
					22.696542705518816
				],
				[
					8.335867248613617,
					22.544011040420266
				],
				[
					8.335867248613617,
					22.2406056631048
				],
				[
					8.48031812916506,
					21.784668620690663
				],
				[
					8.691438646894937,
					21.118171562325312
				],
				[
					8.83588952744638,
					20.965639897226897
				],
				[
					8.83588952744638,
					20.813108232128346
				],
				[
					8.83588952744638,
					20.50970285481275
				],
				[
					8.83588952744638,
					20.66057656702979
				],
				[
					8.83588952744638,
					21.325415672513618
				],
				[
					8.83588952744638,
					22.292002202431405
				],
				[
					8.83588952744638,
					23.852135863928282
				],
				[
					8.83588952744638,
					25.71401694985924
				],
				[
					8.83588952744638,
					26.16663808651035
				],
				[
					8.83588952744638,
					26.77013293537839
				],
				[
					8.83588952744638,
					27.736719465296176
				],
				[
					8.83588952744638,
					28.70330599521408
				],
				[
					8.83588952744638,
					29.519018812914954
				],
				[
					8.83588952744638,
					29.971639949565944
				],
				[
					8.83588952744638,
					30.42426108621708
				],
				[
					8.83588952744638,
					30.876882222868065
				],
				[
					8.83588952744638,
					31.178629647302138
				],
				[
					8.83588952744638,
					31.329503359519187
				],
				[
					8.83588952744638,
					31.48037707173622
				],
				[
					8.83588952744638,
					31.932998208387225
				],
				[
					8.83588952744638,
					32.38561934503834
				],
				[
					8.83588952744638,
					33.05045845052204
				],
				[
					8.83588952744638,
					33.65395329939021
				],
				[
					8.83588952744638,
					33.95570072382428
				],
				[
					8.83588952744638,
					34.10657443604132
				],
				[
					8.689851274580924,
					34.559195572692325
				],
				[
					8.689851274580924,
					34.86094299712639
				],
				[
					8.477143384538028,
					35.676655814827136
				],
				[
					8.477143384538028,
					36.492368632528006
				],
				[
					8.477143384538028,
					36.794116056962096
				],
				[
					8.331105131672572,
					37.24673719361308
				],
				[
					8.331105131672572,
					37.39761090583012
				],
				[
					8.331105131672572,
					37.54848461804716
				],
				[
					8.331105131672572,
					37.85023204248111
				],
				[
					8.331105131672572,
					38.00110575469816
				],
				[
					8.331105131672572,
					37.8485740895996
				],
				[
					8.331105131672572,
					37.392637047185595
				],
				[
					8.331105131672572,
					36.42273461150477
				],
				[
					8.475556012224029,
					35.96679756909062
				],
				[
					8.475556012224029,
					35.359986814459575
				],
				[
					8.475556012224029,
					34.54095809099582
				],
				[
					8.475556012224029,
					33.72192936753192
				],
				[
					8.764457773327415,
					32.448621554535514
				],
				[
					8.764457773327415,
					31.478719118854713
				],
				[
					8.90890865387886,
					30.87190836422353
				],
				[
					9.120029171608735,
					29.90200592854272
				],
				[
					9.120029171608735,
					29.29519517391166
				],
				[
					9.120029171608735,
					28.839258131497527
				],
				[
					9.120029171608735,
					28.383321089083502
				],
				[
					9.264480052160177,
					28.230789423984955
				],
				[
					9.264480052160177,
					27.77485238157094
				],
				[
					9.264480052160177,
					27.46978905137383
				],
				[
					9.264480052160177,
					27.31725738627528
				],
				[
					9.620051450441007,
					26.49822866281139
				],
				[
					9.620051450441007,
					26.345696997712967
				],
				[
					9.620051450441007,
					25.889759955298818
				],
				[
					9.764502330992947,
					25.7372282902004
				],
				[
					9.975622848722328,
					24.9181995667365
				],
				[
					9.975622848722328,
					24.765667901637954
				],
				[
					10.12007372927377,
					24.6131362365394
				],
				[
					10.47564512755509,
					23.794107513075637
				],
				[
					10.620096008106533,
					23.490702135760042
				],
				[
					10.764546888658472,
					23.185638805563066
				],
				[
					10.908997769209922,
					23.033107140464516
				],
				[
					11.197899530313311,
					22.729701763148928
				],
				[
					11.34235041086525,
					22.42629638583333
				],
				[
					11.486801291416693,
					22.273764720734906
				],
				[
					11.775703052520086,
					21.968701390537806
				],
				[
					12.064604813623468,
					21.66363806034083
				],
				[
					12.35350657472685,
					21.35857473014373
				],
				[
					12.497957455278296,
					21.35857473014373
				],
				[
					12.931310096933633,
					21.053511399946622
				],
				[
					13.075760977485078,
					20.90097973484807
				],
				[
					13.220211858037015,
					20.90097973484807
				],
				[
					13.509113619139903,
					20.90097973484807
				],
				[
					14.290100797507506,
					20.90097973484807
				],
				[
					14.434551678058956,
					20.90097973484807
				],
				[
					14.867904319714281,
					20.90097973484807
				],
				[
					15.156806080817663,
					20.90097973484807
				],
				[
					15.590158722472502,
					20.90097973484807
				],
				[
					15.734609603024442,
					20.90097973484807
				],
				[
					15.879060483575884,
					21.051853447065106
				],
				[
					16.167962244679273,
					21.353600871499193
				],
				[
					16.456864005782666,
					21.65534829593327
				],
				[
					16.60131488633411,
					21.806222008150314
				],
				[
					16.74576576688605,
					21.957095720367352
				],
				[
					16.89021664743749,
					22.409716857018342
				],
				[
					17.17911840854088,
					22.862337993669332
				],
				[
					17.323569289092823,
					23.164085418103415
				],
				[
					17.468020169644266,
					23.4658328425375
				],
				[
					17.468020169644266,
					23.76758026697157
				],
				[
					17.612471050196213,
					24.22020140362257
				],
				[
					17.612471050196213,
					24.672822540273682
				],
				[
					17.612471050196213,
					24.8236962524906
				],
				[
					17.612471050196213,
					25.27631738914172
				],
				[
					17.612471050196213,
					25.427191101358755
				],
				[
					17.612471050196213,
					25.72893852579284
				],
				[
					17.612471050196213,
					26.544651343493584
				],
				[
					17.612471050196213,
					27.36036416119446
				],
				[
					17.466432797330256,
					27.66211158562841
				],
				[
					16.790212191670836,
					29.071371534908373
				],
				[
					16.498135685939936,
					29.37311895934245
				],
				[
					16.352097433074977,
					29.6748663837764
				],
				[
					16.061608299657586,
					29.976613808210484
				],
				[
					15.769531793926667,
					30.429234944861477
				],
				[
					15.623493541061219,
					30.580108657078515
				],
				[
					15.33300440764432,
					31.032729793729636
				],
				[
					15.186966154778865,
					31.183603505946678
				],
				[
					14.894889649047954,
					31.485350930380754
				],
				[
					14.60281314331705,
					31.636224642597675
				],
				[
					14.310736637586142,
					31.93797206703175
				],
				[
					14.164698384720687,
					32.08884577924879
				],
				[
					13.728170998438333,
					32.23971949146583
				],
				[
					12.231278906567553,
					32.591205502345005
				],
				[
					12.085240653702105,
					32.74207921456204
				],
				[
					11.939202400836649,
					32.892952926779074
				],
				[
					11.647125895105745,
					32.892952926779074
				],
				[
					11.50108764224029,
					32.892952926779074
				],
				[
					11.064560255957936,
					32.892952926779074
				],
				[
					10.772483750227028,
					32.892952926779074
				],
				[
					10.626445497361573,
					32.892952926779074
				],
				[
					10.335956363944675,
					32.892952926779074
				],
				[
					10.18991811107922,
					32.892952926779074
				],
				[
					9.897841605348315,
					32.892952926779074
				],
				[
					9.259717935218646,
					32.670787240657305
				],
				[
					8.969228801801748,
					32.3673818633417
				],
				[
					8.969228801801748,
					32.3673818633417
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "text",
			"version": 163,
			"versionNonce": 1899419138,
			"isDeleted": false,
			"id": "E9mr608p",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 4265.760039126504,
			"y": 1246.8161886438904,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 107.14498901367188,
			"height": 38.4,
			"seed": 759180479,
			"groupIds": [
				"oN13jXW4IOBOXG_cPqeLH"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029733,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 3,
			"text": "[애플리케이션]\nPHP, 파이썬..",
			"rawText": "[애플리케이션]\nPHP, 파이썬..",
			"textAlign": "center",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "[애플리케이션]\nPHP, 파이썬..",
			"lineHeight": 1.2,
			"baseline": 34
		},
		{
			"type": "rectangle",
			"version": 505,
			"versionNonce": 46859038,
			"isDeleted": false,
			"id": "VmaFQ1_a32cmvuUSyvj2N",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 4092.7917776746735,
			"y": 1518.7926192602142,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 230.04677807215674,
			"height": 0.0816641278047427,
			"seed": 907455633,
			"groupIds": [
				"_jnuME_Jn9OXwxMPO1hle",
				"oN13jXW4IOBOXG_cPqeLH"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029733,
			"link": null,
			"locked": false
		},
		{
			"type": "line",
			"version": 496,
			"versionNonce": 632341954,
			"isDeleted": false,
			"id": "TBTIueM6MxbhoekltZk0b",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 4307.181597611286,
			"y": 1504.8651979200567,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 16.104751117170508,
			"height": 28.00081470680334,
			"seed": 1083503217,
			"groupIds": [
				"_jnuME_Jn9OXwxMPO1hle",
				"oN13jXW4IOBOXG_cPqeLH"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029733,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					16.104751117170508,
					14.027660649139648
				],
				[
					0.8506921598213921,
					28.00081470680334
				]
			]
		},
		{
			"type": "text",
			"version": 313,
			"versionNonce": 1593372510,
			"isDeleted": false,
			"id": "DT5Km479",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 4158.713563935871,
			"y": 1504.9275950648878,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 98.572998046875,
			"height": 29.15906594422691,
			"seed": 206472543,
			"groupIds": [
				"oN13jXW4IOBOXG_cPqeLH"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029733,
			"link": null,
			"locked": false,
			"fontSize": 12.149610810094547,
			"fontFamily": 3,
			"text": "요청 전달\nCGI를 사용한 통신",
			"rawText": "요청 전달\nCGI를 사용한 통신",
			"textAlign": "center",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "요청 전달\nCGI를 사용한 통신",
			"lineHeight": 1.2,
			"baseline": 26
		},
		{
			"type": "rectangle",
			"version": 584,
			"versionNonce": 1557577090,
			"isDeleted": false,
			"id": "R6EsN6u5cFpzxpqWU0qbk",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 4091.731027297309,
			"y": 1613.970283580334,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 230.04677807215674,
			"height": 0.0816641278047427,
			"seed": 1939185279,
			"groupIds": [
				"oN13jXW4IOBOXG_cPqeLH"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029733,
			"link": null,
			"locked": false
		},
		{
			"type": "line",
			"version": 715,
			"versionNonce": 253711262,
			"isDeleted": false,
			"id": "G4DZt-WrQbMVrCuqqWAx_",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 3.147660367579526,
			"x": 4090.525736114594,
			"y": 1599.9751334307641,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 15.904343451141358,
			"height": 27.802824435181265,
			"seed": 1367045791,
			"groupIds": [
				"oN13jXW4IOBOXG_cPqeLH"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029733,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					15.904343451141358,
					13.829670377517573
				],
				[
					0.6502844937922418,
					27.802824435181265
				]
			]
		},
		{
			"type": "text",
			"version": 435,
			"versionNonce": 1944567106,
			"isDeleted": false,
			"id": "72mdNxwK",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 4157.852016194359,
			"y": 1599.908221995198,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 98.572998046875,
			"height": 29.15906594422691,
			"seed": 20007615,
			"groupIds": [
				"oN13jXW4IOBOXG_cPqeLH"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029733,
			"link": null,
			"locked": false,
			"fontSize": 12.149610810094547,
			"fontFamily": 3,
			"text": "응답 반환\nCGI를 사용한 통신",
			"rawText": "응답 반환\nCGI를 사용한 통신",
			"textAlign": "center",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "응답 반환\nCGI를 사용한 통신",
			"lineHeight": 1.2,
			"baseline": 26
		},
		{
			"type": "arrow",
			"version": 872,
			"versionNonce": 1836003294,
			"isDeleted": false,
			"id": "UTkdEGRXc8lpDA2Sg53PD",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 4326.295073221894,
			"y": 1543.0282637903408,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 29.017521866087918,
			"height": 50.10081345436981,
			"seed": 303172561,
			"groupIds": [
				"oN13jXW4IOBOXG_cPqeLH"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029733,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					28.482056636638845,
					0.18519017349137812
				],
				[
					28.597280580960614,
					50.10081345436981
				],
				[
					-0.42024128512730385,
					49.571637841680285
				]
			]
		},
		{
			"type": "text",
			"version": 621,
			"versionNonce": 1212335362,
			"isDeleted": false,
			"id": "AGkGdbFH",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 4360.668148923816,
			"y": 1546.42498901573,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 51.302490234375,
			"height": 45.65127449885019,
			"seed": 476211633,
			"groupIds": [
				"oN13jXW4IOBOXG_cPqeLH"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029733,
			"link": null,
			"locked": false,
			"fontSize": 12.680909583013943,
			"fontFamily": 3,
			"text": "요청 처리\n스크립트\n실행",
			"rawText": "요청 처리\n스크립트\n실행",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "요청 처리\n스크립트\n실행",
			"lineHeight": 1.2,
			"baseline": 42
		},
		{
			"type": "arrow",
			"version": 984,
			"versionNonce": 1710851102,
			"isDeleted": false,
			"id": "aFD_taLfBfBvS198WGhjf",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 4092.6052229014595,
			"y": 1655.651639914445,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 29.017521866087918,
			"height": 50.10081345436981,
			"seed": 1432148657,
			"groupIds": [
				"oN13jXW4IOBOXG_cPqeLH"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029733,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					28.482056636638845,
					0.18519017349137812
				],
				[
					28.597280580960614,
					50.10081345436981
				],
				[
					-0.42024128512730385,
					49.571637841680285
				]
			]
		},
		{
			"type": "text",
			"version": 817,
			"versionNonce": 862377154,
			"isDeleted": false,
			"id": "KWceMxoX",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 4126.688155633772,
			"y": 1658.9617552981597,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 62.27069091796875,
			"height": 45.65127449885019,
			"seed": 254827665,
			"groupIds": [
				"oN13jXW4IOBOXG_cPqeLH"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029733,
			"link": null,
			"locked": false,
			"fontSize": 12.680909583013943,
			"fontFamily": 3,
			"text": "응답 후처리\ngzip 압축\n문자 인코딩",
			"rawText": "응답 후처리\ngzip 압축\n문자 인코딩",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "응답 후처리\ngzip 압축\n문자 인코딩",
			"lineHeight": 1.2,
			"baseline": 42
		},
		{
			"type": "arrow",
			"version": 1031,
			"versionNonce": 984567902,
			"isDeleted": false,
			"id": "ubJZrUpVjLuQgfY4wMve-",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 4092.1420464938747,
			"y": 1435.3899879733829,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 29.017521866087918,
			"height": 50.10081345436981,
			"seed": 439328191,
			"groupIds": [
				"oN13jXW4IOBOXG_cPqeLH"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563029733,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					28.482056636638845,
					0.18519017349137812
				],
				[
					28.597280580960614,
					50.10081345436981
				],
				[
					-0.42024128512730385,
					49.571637841680285
				]
			]
		},
		{
			"type": "rectangle",
			"version": 148,
			"versionNonce": 1263558466,
			"isDeleted": false,
			"id": "gv5QAgx8AzFUfa0iNezhf",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 3886.621368241692,
			"y": 1916.9110270865117,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 446.86224231824235,
			"height": 190.7388941624331,
			"seed": 1263429662,
			"groupIds": [
				"prw3A23Z1WI0oYvFUQdL7"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563072949,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 245,
			"versionNonce": 400141790,
			"isDeleted": false,
			"id": "d_A_s_hF9oOOaUsEp44EH",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 3913.7194341595227,
			"y": 1981.2954757588466,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 58.15967059918967,
			"height": 53.610623669950954,
			"seed": 2103239134,
			"groupIds": [
				"WfeDOMxsuoSsTpZqzKs7Z",
				"prw3A23Z1WI0oYvFUQdL7"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563072949,
			"link": null,
			"locked": false
		},
		{
			"type": "line",
			"version": 996,
			"versionNonce": 776414978,
			"isDeleted": false,
			"id": "8ijIV-JvpLyjNjo8E4dsz",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 3959.517937502576,
			"y": 2000.9779531107386,
			"strokeColor": "#ffd43b",
			"backgroundColor": "#ffd43b",
			"width": 19.369184751161313,
			"height": 24.732307227703764,
			"seed": 2124751042,
			"groupIds": [
				"oA0iJLd5y-tVAwAdclOoI",
				"TlLHobVGBzsNKExPARvx-",
				"WfeDOMxsuoSsTpZqzKs7Z",
				"prw3A23Z1WI0oYvFUQdL7"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563072949,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-11.051993959187019,
					2.5401552549549202
				],
				[
					-18.144047891660858,
					24.732307227703764
				],
				[
					-8.507831247214758,
					23.79456228571221
				],
				[
					-1.4060449191280435,
					16.894866290057358
				],
				[
					1.2251368595004573,
					8.95494895154597
				],
				[
					0,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 1132,
			"versionNonce": 442778142,
			"isDeleted": false,
			"id": "zlf1Dc08JuD6fkVjJChpd",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 2.073978216678766,
			"x": 3943.3034801646295,
			"y": 2000.2849492937164,
			"strokeColor": "#2f9e44",
			"backgroundColor": "#2f9e44",
			"width": 19.369184751161313,
			"height": 24.732307227703764,
			"seed": 475727362,
			"groupIds": [
				"oA0iJLd5y-tVAwAdclOoI",
				"TlLHobVGBzsNKExPARvx-",
				"WfeDOMxsuoSsTpZqzKs7Z",
				"prw3A23Z1WI0oYvFUQdL7"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563072949,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-11.051993959187019,
					2.5401552549549202
				],
				[
					-18.144047891660858,
					24.732307227703764
				],
				[
					-8.507831247214758,
					23.79456228571221
				],
				[
					-1.4060449191280435,
					16.894866290057358
				],
				[
					1.2251368595004573,
					8.95494895154597
				],
				[
					0,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 1197,
			"versionNonce": 1586427586,
			"isDeleted": false,
			"id": "BAldak_sUG0CfOWwuwnB4",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 4.159993704393214,
			"x": 3951.784865443515,
			"y": 1986.1909384100095,
			"strokeColor": "#e03131",
			"backgroundColor": "#e03131",
			"width": 19.369184751161313,
			"height": 24.732307227703764,
			"seed": 1976689922,
			"groupIds": [
				"oA0iJLd5y-tVAwAdclOoI",
				"TlLHobVGBzsNKExPARvx-",
				"WfeDOMxsuoSsTpZqzKs7Z",
				"prw3A23Z1WI0oYvFUQdL7"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563072949,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-11.051993959187019,
					2.5401552549549202
				],
				[
					-18.144047891660858,
					24.732307227703764
				],
				[
					-8.507831247214758,
					23.79456228571221
				],
				[
					-1.4060449191280435,
					16.894866290057358
				],
				[
					1.2251368595004573,
					8.95494895154597
				],
				[
					0,
					0
				]
			]
		},
		{
			"type": "ellipse",
			"version": 831,
			"versionNonce": 1326599774,
			"isDeleted": false,
			"id": "Tl_F5SeInw6u_JCWASQdH",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 3935.299684905013,
			"y": 2000.139566188354,
			"strokeColor": "#ffffff",
			"backgroundColor": "#0091e2",
			"width": 15.654102083570974,
			"height": 15.654102083570974,
			"seed": 1810904386,
			"groupIds": [
				"TlLHobVGBzsNKExPARvx-",
				"WfeDOMxsuoSsTpZqzKs7Z",
				"prw3A23Z1WI0oYvFUQdL7"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563072949,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 103,
			"versionNonce": 482791042,
			"isDeleted": false,
			"id": "h1Z7BTtI",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 3908.199278614391,
			"y": 1954.142344257046,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 69.19998168945312,
			"height": 19.2,
			"seed": 1263968222,
			"groupIds": [
				"prw3A23Z1WI0oYvFUQdL7"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563072949,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 3,
			"text": "클라이언트",
			"rawText": "클라이언트",
			"textAlign": "center",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "클라이언트",
			"lineHeight": 1.2,
			"baseline": 15
		},
		{
			"type": "rectangle",
			"version": 290,
			"versionNonce": 313840286,
			"isDeleted": false,
			"id": "B6o_6H1orGBeC3G4M_ATj",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 4044.8121891478477,
			"y": 1981.1007875938221,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 59,
			"height": 54,
			"seed": 999407938,
			"groupIds": [
				"prw3A23Z1WI0oYvFUQdL7"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"type": "text",
					"id": "nHfE4Bht"
				}
			],
			"updated": 1700563072949,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 18,
			"versionNonce": 1034792514,
			"isDeleted": false,
			"id": "nHfE4Bht",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 4063.7653141478477,
			"y": 1986.5007875938222,
			"strokeColor": "#2f9e44",
			"backgroundColor": "transparent",
			"width": 21.09375,
			"height": 43.199999999999996,
			"seed": 2031294366,
			"groupIds": [
				"prw3A23Z1WI0oYvFUQdL7"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563072949,
			"link": null,
			"locked": false,
			"fontSize": 36,
			"fontFamily": 3,
			"text": "G",
			"rawText": "G",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "B6o_6H1orGBeC3G4M_ATj",
			"originalText": "G",
			"lineHeight": 1.2,
			"baseline": 35
		},
		{
			"type": "line",
			"version": 108,
			"versionNonce": 2147274462,
			"isDeleted": false,
			"id": "71cRrRVEGCVeewu74pTOU",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 3973.184874106317,
			"y": 2008.2216181298186,
			"strokeColor": "#2f9e44",
			"backgroundColor": "transparent",
			"width": 70.01397515821236,
			"height": 0.3111918064105339,
			"seed": 606295874,
			"groupIds": [
				"prw3A23Z1WI0oYvFUQdL7"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563072949,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					70.01397515821236,
					-0.3111918064105339
				]
			]
		},
		{
			"type": "rectangle",
			"version": 459,
			"versionNonce": 639800834,
			"isDeleted": false,
			"id": "ZhD6pd1DwYX26YVLxaAlm",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 4175.859332592189,
			"y": 1956.5367195992678,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 112.67703746958145,
			"height": 103.12813598910844,
			"seed": 335007682,
			"groupIds": [
				"prw3A23Z1WI0oYvFUQdL7"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563072949,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 92,
			"versionNonce": 863716126,
			"isDeleted": false,
			"id": "CUqTje0W",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 4187.761218843351,
			"y": 1930.290801023642,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 83.03997802734375,
			"height": 19.2,
			"seed": 1008082562,
			"groupIds": [
				"prw3A23Z1WI0oYvFUQdL7"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563072949,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 3,
			"text": "애플리케이션",
			"rawText": "애플리케이션",
			"textAlign": "center",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "애플리케이션",
			"lineHeight": 1.2,
			"baseline": 15
		},
		{
			"type": "line",
			"version": 124,
			"versionNonce": 1193575874,
			"isDeleted": false,
			"id": "IhUdWlI_dksRUGbK7ROWo",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 4105.940159160484,
			"y": 2008.2216181298186,
			"strokeColor": "#2f9e44",
			"backgroundColor": "transparent",
			"width": 68.29496146268639,
			"height": 0.241661071992894,
			"seed": 1168309022,
			"groupIds": [
				"prw3A23Z1WI0oYvFUQdL7"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563072949,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					68.29496146268639,
					-0.241661071992894
				]
			]
		},
		{
			"type": "arrow",
			"version": 247,
			"versionNonce": 262221662,
			"isDeleted": false,
			"id": "UrZSjDYrjuZWkRCDTmilw",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 4174.975472216059,
			"y": 2032.8287817263722,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 89.43017497812525,
			"height": 60.4830108598112,
			"seed": 21408222,
			"groupIds": [
				"prw3A23Z1WI0oYvFUQdL7"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563072949,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": "arrow",
			"points": [
				[
					0,
					0
				],
				[
					-45.758692525634615,
					-0.5746604357227625
				],
				[
					-45.349382498303385,
					59.85684783786792
				],
				[
					43.671482452490636,
					59.90835042408844
				],
				[
					43.59287324194429,
					28.697783174509368
				]
			]
		},
		{
			"type": "text",
			"version": 53,
			"versionNonce": 433225090,
			"isDeleted": false,
			"id": "VohtJIvQ",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 4228.742635043535,
			"y": 2079.22447992368,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 92.41497802734375,
			"height": 19.2,
			"seed": 1451520642,
			"groupIds": [
				"prw3A23Z1WI0oYvFUQdL7"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563072949,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 3,
			"text": "프로세스 관리",
			"rawText": "프로세스 관리",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "프로세스 관리",
			"lineHeight": 1.2,
			"baseline": 15
		},
		{
			"type": "rectangle",
			"version": 206,
			"versionNonce": 12555166,
			"isDeleted": false,
			"id": "j_zHpUUkBJ-bwuQtFd9m1",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 4177.829799757643,
			"y": 1984.958483165701,
			"strokeColor": "#da77f2",
			"backgroundColor": "#eebefa",
			"width": 68.46320106154508,
			"height": 55.56315854454351,
			"seed": 1340504798,
			"groupIds": [
				"prw3A23Z1WI0oYvFUQdL7"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563072949,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 670,
			"versionNonce": 460029250,
			"isDeleted": false,
			"id": "nTALk8SIi1a6YccVE8iu-",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 4209.971889910278,
			"y": 1977.398445641028,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#da77f2",
			"width": 48.11257304456559,
			"height": 22.518703534164295,
			"seed": 628392898,
			"groupIds": [
				"prw3A23Z1WI0oYvFUQdL7"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563072949,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 96,
			"versionNonce": 1091006430,
			"isDeleted": false,
			"id": "HLTmfRi2",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 4182.500271129106,
			"y": 2024.1844792286379,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#eebefa",
			"width": 50.849945068359375,
			"height": 13.003673466015295,
			"seed": 1397106718,
			"groupIds": [
				"prw3A23Z1WI0oYvFUQdL7"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563072949,
			"link": null,
			"locked": false,
			"fontSize": 11.307542144361127,
			"fontFamily": 2,
			"text": "PHP-FPM",
			"rawText": "PHP-FPM",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "PHP-FPM",
			"lineHeight": 1.15,
			"baseline": 10
		},
		{
			"type": "text",
			"version": 100,
			"versionNonce": 1229882626,
			"isDeleted": false,
			"id": "yccaS9uw",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 4221.260033253628,
			"y": 1979.2996068384423,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#eebefa",
			"width": 26.26171875,
			"height": 17.92835632561479,
			"seed": 740500254,
			"groupIds": [
				"prw3A23Z1WI0oYvFUQdL7"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563072949,
			"link": null,
			"locked": false,
			"fontSize": 14.940296938012326,
			"fontFamily": 3,
			"text": "PHP",
			"rawText": "PHP",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "PHP",
			"lineHeight": 1.2,
			"baseline": 14
		},
		{
			"type": "text",
			"version": 50,
			"versionNonce": 478790686,
			"isDeleted": false,
			"id": "xuoRwole",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 4049.425720322817,
			"y": 1956.7730151909632,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#eebefa",
			"width": 50.894989013671875,
			"height": 19.2,
			"seed": 889213186,
			"groupIds": [
				"prw3A23Z1WI0oYvFUQdL7"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1700563072949,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 3,
			"text": "웹 서버",
			"rawText": "웹 서버",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "웹 서버",
			"lineHeight": 1.2,
			"baseline": 15
		},
		{
			"id": "Ev1qQnXBogMnRPkuvCSBk",
			"type": "line",
			"x": 1271.0143534496478,
			"y": -483.0713889228829,
			"width": 0.10071088002837314,
			"height": 90.32902702420745,
			"angle": 0,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#eebefa",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"seed": 213124717,
			"version": 94,
			"versionNonce": 1580170659,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1700975490649,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					-0.10071088002837314,
					-90.32902702420745
				]
			],
			"lastCommittedPoint": [
				-0.10071088002837314,
				-90.32902702420745
			],
			"startBinding": null,
			"endBinding": null,
			"startArrowhead": null,
			"endArrowhead": null
		},
		{
			"id": "_3B4Oi4wYy1ZOW3MzX7ov",
			"type": "rectangle",
			"x": 1224.8830154892728,
			"y": -631.8472558080645,
			"width": 93.18921601701004,
			"height": 57.75049606192158,
			"angle": 0,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#eebefa",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"seed": 861262147,
			"version": 81,
			"versionNonce": 2072859203,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1700975495127,
			"link": null,
			"locked": false
		},
		{
			"id": "AkNed2tlpVCKWnfiXE9wN",
			"type": "line",
			"x": 1193.2914511512638,
			"y": -349.34172751392396,
			"width": 79.82919841783223,
			"height": 74.62100719351326,
			"angle": 0,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#eebefa",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"seed": 1499690925,
			"version": 316,
			"versionNonce": 1986958179,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1700975532470,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					79.6565511949268,
					0.008632361145259893
				],
				[
					79.82919841783223,
					-74.612374832368
				]
			],
			"lastCommittedPoint": [
				51.04315145203918,
				-56.19379360205613
			],
			"startBinding": null,
			"endBinding": null,
			"startArrowhead": null,
			"endArrowhead": null
		}
	],
	"appState": {
		"theme": "light",
		"viewBackgroundColor": "#ffffff",
		"currentItemStrokeColor": "#1e1e1e",
		"currentItemBackgroundColor": "#eebefa",
		"currentItemFillStyle": "solid",
		"currentItemStrokeWidth": 2,
		"currentItemStrokeStyle": "solid",
		"currentItemRoughness": 0,
		"currentItemOpacity": 100,
		"currentItemFontFamily": 3,
		"currentItemFontSize": 16,
		"currentItemTextAlign": "left",
		"currentItemStartArrowhead": null,
		"currentItemEndArrowhead": "arrow",
		"scrollX": -842.1960586504455,
		"scrollY": 848.0159661544453,
		"zoom": {
			"value": 1.357537040304193
		},
		"currentItemRoundness": "sharp",
		"gridSize": null,
		"currentStrokeOptions": null,
		"previousGridSize": null
	},
	"files": {}
}
```
%%