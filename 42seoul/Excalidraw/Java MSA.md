---

excalidraw-plugin: parsed
tags: [excalidraw]

---
==⚠  Switch to EXCALIDRAW VIEW in the MORE OPTIONS menu of this document. ⚠==


# Text Elements
Spring Cloud

<Gateway> ^ANyxaf5u

Spring Boot

Config Client
Eureka Client ^klMAQNbI

Spring Boot

Config Client
Eureka Client ^v9eL6zDe

Spring Boot

Config Client
Eureka Client ^iUV61EdF

Spring Cloud

Eureka Server ^PCHQ0nAN

Spring Config Server ^XcnxXITA

Config Repository ^yc8oyAaf

마이크로서비스를 구축, 배포 시 마주하는 문제 ^L5c3VmI9

15-Factor methodology ^eISMpg5C

1.One codebase, one application ^rUCkTfCu

2.API first ^P5l7Szn3

3.Dependency management ^Mzyt5tLy

4.design, build, release, run ^Xs2C9hRy

5.Configuration, credentials & code ^NwD6J0tY

6.Logs ^HShPxy98

7.Disposability ^Rlfn9MfC

8.Backing services ^rNylk4ac

9.environment parity ^guqHT8yn

10.Administrative processes ^AOLBJ4MN

11.Port binding ^d3NzGcFQ

12.Stateless processes ^8ErEnI5e

13.concurrency ^431IWGQK

14.Telemetry ^IN541hg2

15.Authentication & authorization ^1W6cDhlW

Accounts ^Psb17jNa

Loans ^BgzqjMXA

Cards ^3uUniQNK

Message
Broker ^l6YWMVcJ

Config Server ^RNAbJ7JV

github
config repo ^uIh647wL

1.변경사항 push ^5QVfZRuv

2.`domain/actuator/busrefresh` 호출
  - config 서버가 repo에서 최신 데이터를 받아옴 ^jqMdHtCo

3.설정이 바뀐 이벤트를 감지
  - 구독 중인 노드를 새로고침 ^3wH4kL4w

4.새 설정 데이터를 config 서버에서 받아온다 ^hb7jEoPE

10번째 요청 ^1cgCh2pB

OPEN 상태로 전환 ^9GO4Yh6B

회로 차단 패턴에 의해 요청 차단 ^myGnR4rR

Client ^t4YEYIjY

Auth Server ^BdzaVV04

Resource Server ^7MVg015V

리소스 서버의 보호된 자원에 접근하려고 한다.
client credential을 제공한다. ^qHdsn2uW

client credential이 유효하다.
접근 가능한 Access token을 발급한다. ^Q4wfjRoP

보호된 자원에 접근하려고 한다.
Auth server로 부터 발급받은 Access Token을 제공한다. ^AeOYRTWq

토큰이 유효함을 확인했으므로
요청한 리소스를 제공한다. ^qULRLDKM

Client ^sEGqCsXr

Auth Server ^V5eRkDtA

Resource Server ^aigmTlIa

User ^lBKxoWmz

1.resource에 접근할 거야 ^TWPfSIE0

2.auth 서버에서 다음 작업을
수행해 ^gux8RUHb

3.ID/PW 줄테니 client 한테 내 resource에 접근해도 된다고 해줘 ^HB6Z87jL

4.유저 확인 됐으니 AUTHORIZATION CODE(임시) 줄게 ^I3hc1agG

5. 여기 내 credentials와 AUTH CODE야
access token을 주겠니? ^41uXrYNQ

credentials(ID/SECRET)
AUTH CODE 유효성 검사 ^au3dftGl

6.확인 되었으니 access 토큰 줄게 ^Cdg2sAwl

7.Access 토큰 줄게, 유저의 resource 다오.  ^aQMQtR77

유효성 검증 ^m8N1kkim

유저의 ID/PW ^NnjX4Png

Authorization code ^YytE6noV

Client credential ^2nChsSUv

Authorization code ^JJsz5ON1

Access Token ^ugHH2CuG

Access Token ^31vteV69

8.토큰이 유효하니 resource 줄게 ^Yeak6ts2

resource ^Yq42xC6U

1.새 계정 생성 요청 ^YTiq9YiE

2.새 계정을 생성한다.
  event broker에 push한다.
  end user에게 응답한다. ^wOiPKwkA

Account Microservice ^s1TMRscW

3.새 계정 생성 완료 응답 ^Qfcx7JwD

3.event broker가 이벤트의 세부 사항을 큐에 저장한다.
  큐를 구독하고 있는 subscriber가 이벤트를 읽도록 한다. ^ZFdnyKLB

Event broker ^CD2AwPFB

Message
service ^md2SOyCH

4.event broker로부터 알림을 받고 큐의 내용을 읽는다.
  이메일 또는 SMS를 통해 사용자에게 메시지를 전송하도록 한다. ^5SNrjoB5

Message service: 이벤트 브로커 내부에서 queue를 지속적으로 모니터링 하는 서비스 ^OIlqRIxH

Sync | Async ^agTpK3Fk

5.메시지가 사용자에게 전송되면 전송이 완료되었다는 메시지를 이벤트 큐에 push한다. ^6C8sH1YN

6.event broker가 이벤트의 세부 사항을 큐에 저장한다.
  큐를 구독하고 있는 subscriber가 이벤트를 읽도록 한다. ^IKqbQXYW

7.이벤트 브로커의 큐에서 완료되었다는 이벤트를 읽는다.
  전송 되었다는 데이터를 DB에 업데이트한다. ^967EcfBy

reverse asynchronous flow ^KFCBOmQE

Producer ^caPo81WL

Exchange ^D7HafStZ

Queue1 ^Prnc0hgg

Queue1 ^e0Q5TXkt

Consumer1 ^V2J6w4XM

Consumer2 ^OQgM2iWU

message 전송 ^u1TjHEe0

message 수신 ^RtrGqEOw

message 수신 ^xo6ZlviR


# Embedded files
bd8e5d09ac51728154f300e9debe899088772a93: [[Pasted Image 20240711163913_622.png]]
5be777ea66ff22559a46b3f73b92228bd031a0be: [[Pasted Image 20240711165628_986.png]]
ed9384fa8b333cdbfbf3128c8ed0dda48a34747b: [[Pasted Image 20240715151303_495.png]]
5a834bd01d55ddb7a9b46fe579531fc6916cc3b8: [[Pasted Image 20240724181930_171.png]]
2cf2d4ed94e24c697d4cca078a3e8f28b6540573: [[Pasted Image 20240731155704_188.png]]
1bd6f6c757e9a6fa30092af5f7b5e298ef45ce8f: [[Pasted Image 20240807153142_753.png]]

%%
# Drawing
```json
{
	"type": "excalidraw",
	"version": 2,
	"source": "https://github.com/zsviczian/obsidian-excalidraw-plugin/releases/tag/1.9.8",
	"elements": [
		{
			"type": "ellipse",
			"version": 198,
			"versionNonce": 34086062,
			"isDeleted": false,
			"id": "T9uyjPkQnBUDADfRgxLuK",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -134.07356770833331,
			"y": 70.14453125000006,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 174,
			"height": 172,
			"seed": 1677296842,
			"groupIds": [
				"teYq1GTQ6BFnrFdyHFm0C"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [
				{
					"type": "text",
					"id": "ANyxaf5u"
				}
			],
			"updated": 1724916934750,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 282,
			"versionNonce": 395824434,
			"isDeleted": false,
			"id": "ANyxaf5u",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -103.34185767156295,
			"y": 127.53334806795696,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 112.5,
			"height": 57.599999999999994,
			"seed": 1632463958,
			"groupIds": [
				"teYq1GTQ6BFnrFdyHFm0C"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1724916934750,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 3,
			"text": "Spring Cloud\n\n<Gateway>",
			"rawText": "Spring Cloud\n\n<Gateway>",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "T9uyjPkQnBUDADfRgxLuK",
			"originalText": "Spring Cloud\n\n<Gateway>",
			"lineHeight": 1.2,
			"baseline": 53
		},
		{
			"type": "rectangle",
			"version": 220,
			"versionNonce": 679237358,
			"isDeleted": false,
			"id": "3cc2fjG0Djj1LQ7d8nW1P",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 194.70703125,
			"y": -101.61690306432041,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 142,
			"height": 120,
			"seed": 571107210,
			"groupIds": [
				"teYq1GTQ6BFnrFdyHFm0C"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"type": "text",
					"id": "klMAQNbI"
				}
			],
			"updated": 1724916934750,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 322,
			"versionNonce": 1833654002,
			"isDeleted": false,
			"id": "klMAQNbI",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 206.2548828125,
			"y": -79.08361904065177,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 118.904296875,
			"height": 74.93343195266272,
			"seed": 1202230998,
			"groupIds": [
				"teYq1GTQ6BFnrFdyHFm0C"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1724916934750,
			"link": null,
			"locked": false,
			"fontSize": 15.611131656804732,
			"fontFamily": 3,
			"text": "Spring Boot\n\nConfig Client\nEureka Client",
			"rawText": "Spring Boot\n\nConfig Client\nEureka Client",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "3cc2fjG0Djj1LQ7d8nW1P",
			"originalText": "Spring Boot\n\nConfig Client\nEureka Client",
			"lineHeight": 1.2,
			"baseline": 70
		},
		{
			"type": "rectangle",
			"version": 254,
			"versionNonce": 1626294574,
			"isDeleted": false,
			"id": "KXit7uOKAo6cEzTgHYcnC",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 194.70703125,
			"y": 96.14453125000006,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 142,
			"height": 120,
			"seed": 1301319370,
			"groupIds": [
				"teYq1GTQ6BFnrFdyHFm0C"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"type": "text",
					"id": "v9eL6zDe"
				}
			],
			"updated": 1724916934750,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 356,
			"versionNonce": 1600628914,
			"isDeleted": false,
			"id": "v9eL6zDe",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 206.2548828125,
			"y": 118.6778152736687,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 118.904296875,
			"height": 74.93343195266272,
			"seed": 1055401354,
			"groupIds": [
				"teYq1GTQ6BFnrFdyHFm0C"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1724916934751,
			"link": null,
			"locked": false,
			"fontSize": 15.611131656804732,
			"fontFamily": 3,
			"text": "Spring Boot\n\nConfig Client\nEureka Client",
			"rawText": "Spring Boot\n\nConfig Client\nEureka Client",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "KXit7uOKAo6cEzTgHYcnC",
			"originalText": "Spring Boot\n\nConfig Client\nEureka Client",
			"lineHeight": 1.2,
			"baseline": 70
		},
		{
			"type": "rectangle",
			"version": 285,
			"versionNonce": 1791619950,
			"isDeleted": false,
			"id": "KULif3sZpENySZUEGhMVz",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 194.44227430555554,
			"y": 297.9276669532093,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 142,
			"height": 120,
			"seed": 1744336906,
			"groupIds": [
				"teYq1GTQ6BFnrFdyHFm0C"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"type": "text",
					"id": "iUV61EdF"
				}
			],
			"updated": 1724916934751,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 388,
			"versionNonce": 1972617842,
			"isDeleted": false,
			"id": "iUV61EdF",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 205.99012586805554,
			"y": 320.46095097687794,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 118.904296875,
			"height": 74.93343195266272,
			"seed": 788588234,
			"groupIds": [
				"teYq1GTQ6BFnrFdyHFm0C"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1724916934751,
			"link": null,
			"locked": false,
			"fontSize": 15.611131656804732,
			"fontFamily": 3,
			"text": "Spring Boot\n\nConfig Client\nEureka Client",
			"rawText": "Spring Boot\n\nConfig Client\nEureka Client",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "KULif3sZpENySZUEGhMVz",
			"originalText": "Spring Boot\n\nConfig Client\nEureka Client",
			"lineHeight": 1.2,
			"baseline": 70
		},
		{
			"type": "rectangle",
			"version": 304,
			"versionNonce": 810898862,
			"isDeleted": false,
			"id": "FNlPhQ3p0gg-lVbQQBuxf",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -79.37413194444451,
			"y": 336.81119791666674,
			"strokeColor": "#1971c2",
			"backgroundColor": "transparent",
			"width": 142,
			"height": 120,
			"seed": 433470550,
			"groupIds": [
				"teYq1GTQ6BFnrFdyHFm0C"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"type": "text",
					"id": "PCHQ0nAN"
				}
			],
			"updated": 1724916934751,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 447,
			"versionNonce": 714515506,
			"isDeleted": false,
			"id": "PCHQ0nAN",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -67.82628038194451,
			"y": 368.7111609344182,
			"strokeColor": "#1971c2",
			"backgroundColor": "transparent",
			"width": 118.904296875,
			"height": 56.20007396449704,
			"seed": 599277974,
			"groupIds": [
				"teYq1GTQ6BFnrFdyHFm0C"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1724916934751,
			"link": null,
			"locked": false,
			"fontSize": 15.611131656804732,
			"fontFamily": 3,
			"text": "Spring Cloud\n\nEureka Server",
			"rawText": "Spring Cloud\n\nEureka Server",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "FNlPhQ3p0gg-lVbQQBuxf",
			"originalText": "Spring Cloud\n\nEureka Server",
			"lineHeight": 1.2,
			"baseline": 51
		},
		{
			"type": "line",
			"version": 157,
			"versionNonce": 1790603246,
			"isDeleted": false,
			"id": "6vxYhjzmfnKdQvccOiNe2",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 40.74045138888886,
			"y": 161.42057291666663,
			"strokeColor": "#1971c2",
			"backgroundColor": "transparent",
			"width": 154.12760416666663,
			"height": 211.48437500000003,
			"seed": 1144786506,
			"groupIds": [
				"teYq1GTQ6BFnrFdyHFm0C"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1724916934751,
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
					154.12760416666663,
					-211.48437500000003
				]
			]
		},
		{
			"type": "line",
			"version": 188,
			"versionNonce": 139939314,
			"isDeleted": false,
			"id": "sjz_gCi6u5mnxB7FMAH-M",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 195.07204861111114,
			"y": 162.4578993055555,
			"strokeColor": "#1971c2",
			"backgroundColor": "transparent",
			"width": 154.01909722222229,
			"height": 205.8420138888889,
			"seed": 409924822,
			"groupIds": [
				"teYq1GTQ6BFnrFdyHFm0C"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1724916934751,
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
					-154.01909722222229,
					0
				],
				[
					-0.6727430555556566,
					205.8420138888889
				]
			]
		},
		{
			"type": "rectangle",
			"version": 333,
			"versionNonce": 1174553134,
			"isDeleted": false,
			"id": "gj1lShjY-IfDvQHJ7WVfs",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 444.1935763888888,
			"y": -63.11690306432041,
			"strokeColor": "#1971c2",
			"backgroundColor": "transparent",
			"width": 215,
			"height": 43,
			"seed": 805062038,
			"groupIds": [
				"teYq1GTQ6BFnrFdyHFm0C"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"type": "text",
					"id": "XcnxXITA"
				}
			],
			"updated": 1724916934751,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 487,
			"versionNonce": 1138540466,
			"isDeleted": false,
			"id": "XcnxXITA",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 460.2287326388888,
			"y": -50.98358205840325,
			"strokeColor": "#1971c2",
			"backgroundColor": "transparent",
			"width": 182.9296875,
			"height": 18.73335798816568,
			"seed": 852173526,
			"groupIds": [
				"teYq1GTQ6BFnrFdyHFm0C"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1724916934751,
			"link": null,
			"locked": false,
			"fontSize": 15.611131656804732,
			"fontFamily": 3,
			"text": "Spring Config Server",
			"rawText": "Spring Config Server",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "gj1lShjY-IfDvQHJ7WVfs",
			"originalText": "Spring Config Server",
			"lineHeight": 1.2,
			"baseline": 14
		},
		{
			"type": "rectangle",
			"version": 190,
			"versionNonce": 85314670,
			"isDeleted": false,
			"id": "DqSONYVD1IHYp3MpDDlo7",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 727.6067708333333,
			"y": -66.11690306432041,
			"strokeColor": "#e03131",
			"backgroundColor": "transparent",
			"width": 146,
			"height": 49,
			"seed": 152618518,
			"groupIds": [
				"teYq1GTQ6BFnrFdyHFm0C"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"type": "text",
					"id": "yc8oyAaf"
				}
			],
			"updated": 1724916934751,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 225,
			"versionNonce": 1498282354,
			"isDeleted": false,
			"id": "yc8oyAaf",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 753.7317708333333,
			"y": -60.816903064320414,
			"strokeColor": "#e03131",
			"backgroundColor": "transparent",
			"width": 93.75,
			"height": 38.4,
			"seed": 544954826,
			"groupIds": [
				"teYq1GTQ6BFnrFdyHFm0C"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1724916934751,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 3,
			"text": "Config \nRepository",
			"rawText": "Config Repository",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "DqSONYVD1IHYp3MpDDlo7",
			"originalText": "Config Repository",
			"lineHeight": 1.2,
			"baseline": 34
		},
		{
			"type": "line",
			"version": 83,
			"versionNonce": 633212590,
			"isDeleted": false,
			"id": "rFsZbuMe0ZHlrT8oMcJiH",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 339.24739583333337,
			"y": -41.61690306432041,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 103.69357638888891,
			"height": 0,
			"seed": 1688023702,
			"groupIds": [
				"teYq1GTQ6BFnrFdyHFm0C"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1724916934751,
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
					103.69357638888891,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 82,
			"versionNonce": 670169906,
			"isDeleted": false,
			"id": "wguPRTRZ0OXNYOOOY_mLt",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 660.9270833333334,
			"y": -41.61690306432041,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 67.24826388888891,
			"height": 0,
			"seed": 653013514,
			"groupIds": [
				"teYq1GTQ6BFnrFdyHFm0C"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1724916934751,
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
					67.24826388888891,
					0
				]
			]
		},
		{
			"type": "image",
			"version": 93,
			"versionNonce": 77859054,
			"isDeleted": false,
			"id": "1fc8QDi1CPZAew2vgCrFg",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -158.44681294692214,
			"y": 590.8236802630256,
			"strokeColor": "transparent",
			"backgroundColor": "transparent",
			"width": 1256.4590922441319,
			"height": 518.2893755507043,
			"seed": 2089713034,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1724916934751,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "bd8e5d09ac51728154f300e9debe899088772a93",
			"scale": [
				1,
				1
			]
		},
		{
			"type": "image",
			"version": 85,
			"versionNonce": 238011634,
			"isDeleted": false,
			"id": "bbd2834ln_5KVDAtQ3Gop",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -44.63505801795452,
			"y": 1170.6924568583386,
			"strokeColor": "transparent",
			"backgroundColor": "transparent",
			"width": 921.4033343123632,
			"height": 518.2893755507043,
			"seed": 2091689226,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1724916934751,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "5be777ea66ff22559a46b3f73b92228bd031a0be",
			"scale": [
				1,
				1
			]
		},
		{
			"type": "text",
			"version": 213,
			"versionNonce": 22068014,
			"isDeleted": false,
			"id": "L5c3VmI9",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -22.62109599621442,
			"y": 1194.336517378021,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 319.2099304199219,
			"height": 19.2,
			"seed": 1999946070,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1724916934751,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 3,
			"text": "마이크로서비스를 구축, 배포 시 마주하는 문제",
			"rawText": "마이크로서비스를 구축, 배포 시 마주하는 문제",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "마이크로서비스를 구축, 배포 시 마주하는 문제",
			"lineHeight": 1.2,
			"baseline": 15
		},
		{
			"type": "text",
			"version": 152,
			"versionNonce": 93214386,
			"isDeleted": false,
			"id": "eISMpg5C",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -140.8952925674825,
			"y": 1728.0937794840943,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 196.875,
			"height": 19.2,
			"seed": 1278607434,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1724916934751,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 3,
			"text": "15-Factor methodology",
			"rawText": "15-Factor methodology",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "15-Factor methodology",
			"lineHeight": 1.2,
			"baseline": 15
		},
		{
			"type": "rectangle",
			"version": 173,
			"versionNonce": 573384046,
			"isDeleted": false,
			"id": "ssHQNhhypT7I72KI3kjxu",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -143.56644168098353,
			"y": 1801.2981072402322,
			"strokeColor": "transparent",
			"backgroundColor": "#e7f5ff",
			"width": 359,
			"height": 30,
			"seed": 1490080918,
			"groupIds": [
				"4XtcMaU0l4FPRKuWj4gmy"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"type": "text",
					"id": "rUCkTfCu"
				}
			],
			"updated": 1724916934751,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 149,
			"versionNonce": 1052029042,
			"isDeleted": false,
			"id": "rUCkTfCu",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -138.56644168098353,
			"y": 1806.6981072402323,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#e7f5ff",
			"width": 290.625,
			"height": 19.2,
			"seed": 1325070806,
			"groupIds": [
				"4XtcMaU0l4FPRKuWj4gmy"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1724916934751,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 3,
			"text": "1.One codebase, one application",
			"rawText": "1.One codebase, one application",
			"textAlign": "left",
			"verticalAlign": "middle",
			"containerId": "ssHQNhhypT7I72KI3kjxu",
			"originalText": "1.One codebase, one application",
			"lineHeight": 1.2,
			"baseline": 15
		},
		{
			"type": "rectangle",
			"version": 212,
			"versionNonce": 948062126,
			"isDeleted": false,
			"id": "f9XTrtK_YSoersuTjw-M9",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -143.56644168098353,
			"y": 1853.4998030522097,
			"strokeColor": "transparent",
			"backgroundColor": "#e7f5ff",
			"width": 359,
			"height": 30,
			"seed": 1588627274,
			"groupIds": [
				"4XtcMaU0l4FPRKuWj4gmy"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"type": "text",
					"id": "P5l7Szn3"
				}
			],
			"updated": 1724916934751,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 189,
			"versionNonce": 1030345266,
			"isDeleted": false,
			"id": "P5l7Szn3",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -138.56644168098353,
			"y": 1858.8998030522098,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#e7f5ff",
			"width": 103.125,
			"height": 19.2,
			"seed": 175443466,
			"groupIds": [
				"4XtcMaU0l4FPRKuWj4gmy"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1724916934751,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 3,
			"text": "2.API first",
			"rawText": "2.API first",
			"textAlign": "left",
			"verticalAlign": "middle",
			"containerId": "f9XTrtK_YSoersuTjw-M9",
			"originalText": "2.API first",
			"lineHeight": 1.2,
			"baseline": 15
		},
		{
			"type": "rectangle",
			"version": 237,
			"versionNonce": 75047406,
			"isDeleted": false,
			"id": "WFvlv_5Y8nFf_TCOWTMs7",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -143.56644168098353,
			"y": 1905.7014988641872,
			"strokeColor": "transparent",
			"backgroundColor": "#e7f5ff",
			"width": 359,
			"height": 30,
			"seed": 1868400854,
			"groupIds": [
				"4XtcMaU0l4FPRKuWj4gmy"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"type": "text",
					"id": "Mzyt5tLy"
				}
			],
			"updated": 1724916934751,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 216,
			"versionNonce": 1955904498,
			"isDeleted": false,
			"id": "Mzyt5tLy",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -138.56644168098353,
			"y": 1911.1014988641873,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#e7f5ff",
			"width": 215.625,
			"height": 19.2,
			"seed": 1403125270,
			"groupIds": [
				"4XtcMaU0l4FPRKuWj4gmy"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1724916934751,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 3,
			"text": "3.Dependency management",
			"rawText": "3.Dependency management",
			"textAlign": "left",
			"verticalAlign": "middle",
			"containerId": "WFvlv_5Y8nFf_TCOWTMs7",
			"originalText": "3.Dependency management",
			"lineHeight": 1.2,
			"baseline": 15
		},
		{
			"type": "rectangle",
			"version": 266,
			"versionNonce": 1494922286,
			"isDeleted": false,
			"id": "UPZgbuFF5i61vBTR3-Pjm",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -143.56644168098353,
			"y": 1957.9031946761647,
			"strokeColor": "transparent",
			"backgroundColor": "#e7f5ff",
			"width": 359,
			"height": 30,
			"seed": 582195402,
			"groupIds": [
				"4XtcMaU0l4FPRKuWj4gmy"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"type": "text",
					"id": "Xs2C9hRy"
				}
			],
			"updated": 1724916934751,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 247,
			"versionNonce": 1648127410,
			"isDeleted": false,
			"id": "Xs2C9hRy",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -138.56644168098353,
			"y": 1963.3031946761648,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#e7f5ff",
			"width": 271.875,
			"height": 19.2,
			"seed": 1327099786,
			"groupIds": [
				"4XtcMaU0l4FPRKuWj4gmy"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1724916934751,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 3,
			"text": "4.design, build, release, run",
			"rawText": "4.design, build, release, run",
			"textAlign": "left",
			"verticalAlign": "middle",
			"containerId": "UPZgbuFF5i61vBTR3-Pjm",
			"originalText": "4.design, build, release, run",
			"lineHeight": 1.2,
			"baseline": 15
		},
		{
			"type": "rectangle",
			"version": 287,
			"versionNonce": 1078984302,
			"isDeleted": false,
			"id": "mxJEE3RlssGXR_ohCwctG",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -143.56644168098353,
			"y": 2010.1048904881422,
			"strokeColor": "transparent",
			"backgroundColor": "#e7f5ff",
			"width": 359,
			"height": 30,
			"seed": 2085765270,
			"groupIds": [
				"4XtcMaU0l4FPRKuWj4gmy"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"type": "text",
					"id": "NwD6J0tY"
				}
			],
			"updated": 1724916934751,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 270,
			"versionNonce": 730326898,
			"isDeleted": false,
			"id": "NwD6J0tY",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -138.56644168098353,
			"y": 2015.5048904881423,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#e7f5ff",
			"width": 328.125,
			"height": 19.2,
			"seed": 413777366,
			"groupIds": [
				"4XtcMaU0l4FPRKuWj4gmy"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1724916934751,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 3,
			"text": "5.Configuration, credentials & code",
			"rawText": "5.Configuration, credentials & code",
			"textAlign": "left",
			"verticalAlign": "middle",
			"containerId": "mxJEE3RlssGXR_ohCwctG",
			"originalText": "5.Configuration, credentials & code",
			"lineHeight": 1.2,
			"baseline": 15
		},
		{
			"type": "rectangle",
			"version": 301,
			"versionNonce": 518127790,
			"isDeleted": false,
			"id": "cJbfq2Tm5zNFQI5Ln8R8H",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -143.56644168098353,
			"y": 2062.3065863001198,
			"strokeColor": "transparent",
			"backgroundColor": "#e7f5ff",
			"width": 359,
			"height": 30,
			"seed": 1471455114,
			"groupIds": [
				"4XtcMaU0l4FPRKuWj4gmy"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"type": "text",
					"id": "HShPxy98"
				}
			],
			"updated": 1724916934751,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 285,
			"versionNonce": 951986482,
			"isDeleted": false,
			"id": "HShPxy98",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -138.56644168098353,
			"y": 2067.70658630012,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#e7f5ff",
			"width": 56.25,
			"height": 19.2,
			"seed": 869015114,
			"groupIds": [
				"4XtcMaU0l4FPRKuWj4gmy"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1724916934751,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 3,
			"text": "6.Logs",
			"rawText": "6.Logs",
			"textAlign": "left",
			"verticalAlign": "middle",
			"containerId": "cJbfq2Tm5zNFQI5Ln8R8H",
			"originalText": "6.Logs",
			"lineHeight": 1.2,
			"baseline": 15
		},
		{
			"type": "rectangle",
			"version": 330,
			"versionNonce": 1484372718,
			"isDeleted": false,
			"id": "CX6X7b10lXFcAKXXZqtgf",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -143.56644168098353,
			"y": 2114.5082821120973,
			"strokeColor": "transparent",
			"backgroundColor": "#e7f5ff",
			"width": 359,
			"height": 30,
			"seed": 2037108502,
			"groupIds": [
				"4XtcMaU0l4FPRKuWj4gmy"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"type": "text",
					"id": "Rlfn9MfC"
				}
			],
			"updated": 1724916934751,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 316,
			"versionNonce": 1363555058,
			"isDeleted": false,
			"id": "Rlfn9MfC",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": -138.56644168098353,
			"y": 2119.9082821120974,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#e7f5ff",
			"width": 140.625,
			"height": 19.2,
			"seed": 143490134,
			"groupIds": [
				"4XtcMaU0l4FPRKuWj4gmy"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1724916934752,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 3,
			"text": "7.Disposability",
			"rawText": "7.Disposability",
			"textAlign": "left",
			"verticalAlign": "middle",
			"containerId": "CX6X7b10lXFcAKXXZqtgf",
			"originalText": "7.Disposability",
			"lineHeight": 1.2,
			"baseline": 15
		},
		{
			"type": "rectangle",
			"version": 203,
			"versionNonce": 1939877166,
			"isDeleted": false,
			"id": "k_Q32YsnYx3uG2IoqvtVY",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 269.57857157355943,
			"y": 1801.2981072402322,
			"strokeColor": "transparent",
			"backgroundColor": "#e7f5ff",
			"width": 359,
			"height": 30,
			"seed": 364326346,
			"groupIds": [
				"4XtcMaU0l4FPRKuWj4gmy"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"type": "text",
					"id": "rNylk4ac"
				}
			],
			"updated": 1724916934752,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 188,
			"versionNonce": 933692594,
			"isDeleted": false,
			"id": "rNylk4ac",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 274.57857157355943,
			"y": 1806.6981072402323,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#e7f5ff",
			"width": 168.75,
			"height": 19.2,
			"seed": 652403850,
			"groupIds": [
				"4XtcMaU0l4FPRKuWj4gmy"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1724916934752,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 3,
			"text": "8.Backing services",
			"rawText": "8.Backing services",
			"textAlign": "left",
			"verticalAlign": "middle",
			"containerId": "k_Q32YsnYx3uG2IoqvtVY",
			"originalText": "8.Backing services",
			"lineHeight": 1.2,
			"baseline": 15
		},
		{
			"type": "rectangle",
			"version": 220,
			"versionNonce": 1035884398,
			"isDeleted": false,
			"id": "Dv1Ww0_WO4VKM981p5Yrn",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 269.57857157355943,
			"y": 1853.4998030522097,
			"strokeColor": "transparent",
			"backgroundColor": "#e7f5ff",
			"width": 359,
			"height": 30,
			"seed": 300647882,
			"groupIds": [
				"4XtcMaU0l4FPRKuWj4gmy"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"type": "text",
					"id": "guqHT8yn"
				}
			],
			"updated": 1724916934752,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 47,
			"versionNonce": 1166515826,
			"isDeleted": false,
			"id": "guqHT8yn",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 274.57857157355943,
			"y": 1858.8998030522098,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#e7f5ff",
			"width": 187.5,
			"height": 19.2,
			"seed": 1496949770,
			"groupIds": [
				"4XtcMaU0l4FPRKuWj4gmy"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1724916934752,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 3,
			"text": "9.environment parity",
			"rawText": "9.environment parity",
			"textAlign": "left",
			"verticalAlign": "middle",
			"containerId": "Dv1Ww0_WO4VKM981p5Yrn",
			"originalText": "9.environment parity",
			"lineHeight": 1.2,
			"baseline": 15
		},
		{
			"type": "rectangle",
			"version": 244,
			"versionNonce": 1864186286,
			"isDeleted": false,
			"id": "to9LoKjXnelsUv0TnXv5d",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 269.57857157355943,
			"y": 1905.7014988641872,
			"strokeColor": "transparent",
			"backgroundColor": "#e7f5ff",
			"width": 359,
			"height": 30,
			"seed": 1478169674,
			"groupIds": [
				"4XtcMaU0l4FPRKuWj4gmy"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"type": "text",
					"id": "AOLBJ4MN"
				}
			],
			"updated": 1724916934752,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 72,
			"versionNonce": 128909362,
			"isDeleted": false,
			"id": "AOLBJ4MN",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 274.57857157355943,
			"y": 1911.1014988641873,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#e7f5ff",
			"width": 253.125,
			"height": 19.2,
			"seed": 1896217354,
			"groupIds": [
				"4XtcMaU0l4FPRKuWj4gmy"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1724916934752,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 3,
			"text": "10.Administrative processes",
			"rawText": "10.Administrative processes",
			"textAlign": "left",
			"verticalAlign": "middle",
			"containerId": "to9LoKjXnelsUv0TnXv5d",
			"originalText": "10.Administrative processes",
			"lineHeight": 1.2,
			"baseline": 15
		},
		{
			"type": "rectangle",
			"version": 237,
			"versionNonce": 1323684846,
			"isDeleted": false,
			"id": "npEyRaQZRcI1fU026U9Vg",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 269.57857157355943,
			"y": 1957.9031946761647,
			"strokeColor": "transparent",
			"backgroundColor": "#e7f5ff",
			"width": 359,
			"height": 30,
			"seed": 2123313302,
			"groupIds": [
				"4XtcMaU0l4FPRKuWj4gmy"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"type": "text",
					"id": "d3NzGcFQ"
				}
			],
			"updated": 1724916934752,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 66,
			"versionNonce": 1510222322,
			"isDeleted": false,
			"id": "d3NzGcFQ",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 274.57857157355943,
			"y": 1963.3031946761648,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#e7f5ff",
			"width": 140.625,
			"height": 19.2,
			"seed": 633908694,
			"groupIds": [
				"4XtcMaU0l4FPRKuWj4gmy"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1724916934752,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 3,
			"text": "11.Port binding",
			"rawText": "11.Port binding",
			"textAlign": "left",
			"verticalAlign": "middle",
			"containerId": "npEyRaQZRcI1fU026U9Vg",
			"originalText": "11.Port binding",
			"lineHeight": 1.2,
			"baseline": 15
		},
		{
			"type": "rectangle",
			"version": 240,
			"versionNonce": 1461790254,
			"isDeleted": false,
			"id": "rxjyuaOVQDYfu8y-xslr8",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 269.57857157355943,
			"y": 2010.1048904881422,
			"strokeColor": "transparent",
			"backgroundColor": "#e7f5ff",
			"width": 359,
			"height": 30,
			"seed": 34983638,
			"groupIds": [
				"4XtcMaU0l4FPRKuWj4gmy"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"type": "text",
					"id": "8ErEnI5e"
				}
			],
			"updated": 1724916934752,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 71,
			"versionNonce": 59644850,
			"isDeleted": false,
			"id": "8ErEnI5e",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 274.57857157355943,
			"y": 2015.5048904881423,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#e7f5ff",
			"width": 206.25,
			"height": 19.2,
			"seed": 862028822,
			"groupIds": [
				"4XtcMaU0l4FPRKuWj4gmy"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1724916934752,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 3,
			"text": "12.Stateless processes",
			"rawText": "12.Stateless processes",
			"textAlign": "left",
			"verticalAlign": "middle",
			"containerId": "rxjyuaOVQDYfu8y-xslr8",
			"originalText": "12.Stateless processes",
			"lineHeight": 1.2,
			"baseline": 15
		},
		{
			"type": "rectangle",
			"version": 254,
			"versionNonce": 1488466030,
			"isDeleted": false,
			"id": "lA3XuynvNzy5DB_NMvD7p",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 269.57857157355943,
			"y": 2062.3065863001198,
			"strokeColor": "transparent",
			"backgroundColor": "#e7f5ff",
			"width": 359,
			"height": 30,
			"seed": 1224533450,
			"groupIds": [
				"4XtcMaU0l4FPRKuWj4gmy"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"type": "text",
					"id": "431IWGQK"
				}
			],
			"updated": 1724916934752,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 84,
			"versionNonce": 1383322994,
			"isDeleted": false,
			"id": "431IWGQK",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 274.57857157355943,
			"y": 2067.70658630012,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#e7f5ff",
			"width": 131.25,
			"height": 19.2,
			"seed": 1488034954,
			"groupIds": [
				"4XtcMaU0l4FPRKuWj4gmy"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1724916934752,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 3,
			"text": "13.concurrency",
			"rawText": "13.concurrency",
			"textAlign": "left",
			"verticalAlign": "middle",
			"containerId": "lA3XuynvNzy5DB_NMvD7p",
			"originalText": "13.concurrency",
			"lineHeight": 1.2,
			"baseline": 15
		},
		{
			"type": "rectangle",
			"version": 270,
			"versionNonce": 527692462,
			"isDeleted": false,
			"id": "Gum8xym4DOZLocWCuc7Ef",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 269.57857157355943,
			"y": 2114.5082821120973,
			"strokeColor": "transparent",
			"backgroundColor": "#e7f5ff",
			"width": 359,
			"height": 30,
			"seed": 432183702,
			"groupIds": [
				"4XtcMaU0l4FPRKuWj4gmy"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"type": "text",
					"id": "IN541hg2"
				}
			],
			"updated": 1724916934752,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 102,
			"versionNonce": 939284274,
			"isDeleted": false,
			"id": "IN541hg2",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 274.57857157355943,
			"y": 2119.9082821120974,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#e7f5ff",
			"width": 112.5,
			"height": 19.2,
			"seed": 950466262,
			"groupIds": [
				"4XtcMaU0l4FPRKuWj4gmy"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1724916934752,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 3,
			"text": "14.Telemetry",
			"rawText": "14.Telemetry",
			"textAlign": "left",
			"verticalAlign": "middle",
			"containerId": "Gum8xym4DOZLocWCuc7Ef",
			"originalText": "14.Telemetry",
			"lineHeight": 1.2,
			"baseline": 15
		},
		{
			"type": "rectangle",
			"version": 334,
			"versionNonce": 368930030,
			"isDeleted": false,
			"id": "P9WOqQrDYcoVWVn41G269",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 269.57857157355943,
			"y": 2171.2236162925856,
			"strokeColor": "transparent",
			"backgroundColor": "#e7f5ff",
			"width": 359,
			"height": 30,
			"seed": 575123210,
			"groupIds": [
				"4XtcMaU0l4FPRKuWj4gmy"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"type": "text",
					"id": "1W6cDhlW"
				}
			],
			"updated": 1724916934752,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 166,
			"versionNonce": 1687068914,
			"isDeleted": false,
			"id": "1W6cDhlW",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 274.57857157355943,
			"y": 2176.6236162925857,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#e7f5ff",
			"width": 309.375,
			"height": 19.2,
			"seed": 1750154698,
			"groupIds": [
				"4XtcMaU0l4FPRKuWj4gmy"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1724916934752,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 3,
			"text": "15.Authentication & authorization",
			"rawText": "15.Authentication & authorization",
			"textAlign": "left",
			"verticalAlign": "middle",
			"containerId": "P9WOqQrDYcoVWVn41G269",
			"originalText": "15.Authentication & authorization",
			"lineHeight": 1.2,
			"baseline": 15
		},
		{
			"type": "image",
			"version": 57,
			"versionNonce": 1776131886,
			"isDeleted": false,
			"id": "edoTI4rvbnZnW4VNB275D",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 18.09328005014379,
			"y": 2424.4947628641326,
			"strokeColor": "transparent",
			"backgroundColor": "#e7f5ff",
			"width": 420,
			"height": 383,
			"seed": 1287645782,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1724916934752,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "ed9384fa8b333cdbfbf3128c8ed0dda48a34747b",
			"scale": [
				1,
				1
			]
		},
		{
			"type": "rectangle",
			"version": 98,
			"versionNonce": 1672590002,
			"isDeleted": false,
			"id": "0Q6Wr7ATusv5OCpos5iGM",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 59.75172060256449,
			"y": 2987.2480157036975,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#e7f5ff",
			"width": 126,
			"height": 48,
			"seed": 1682477270,
			"groupIds": [
				"w09guj3OGZoaIQl_nalVH"
			],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"type": "text",
					"id": "Psb17jNa"
				}
			],
			"updated": 1724916934752,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 70,
			"versionNonce": 796756334,
			"isDeleted": false,
			"id": "Psb17jNa",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 85.25172060256449,
			"y": 3001.6480157036976,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#e7f5ff",
			"width": 75,
			"height": 19.2,
			"seed": 2119504266,
			"groupIds": [
				"w09guj3OGZoaIQl_nalVH"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1724916934752,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 3,
			"text": "Accounts",
			"rawText": "Accounts",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "0Q6Wr7ATusv5OCpos5iGM",
			"originalText": "Accounts",
			"lineHeight": 1.2,
			"baseline": 15
		},
		{
			"type": "rectangle",
			"version": 193,
			"versionNonce": 940346482,
			"isDeleted": false,
			"id": "e-nlqIpQDujQMsdxMclbA",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 116.90641968307011,
			"y": 3048.348938771596,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#e7f5ff",
			"width": 126,
			"height": 48,
			"seed": 516001622,
			"groupIds": [
				"w09guj3OGZoaIQl_nalVH"
			],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"type": "text",
					"id": "BgzqjMXA"
				}
			],
			"updated": 1724916934752,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 185,
			"versionNonce": 103164846,
			"isDeleted": false,
			"id": "BgzqjMXA",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 156.4689196830701,
			"y": 3062.748938771596,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#e7f5ff",
			"width": 46.875,
			"height": 19.2,
			"seed": 901854358,
			"groupIds": [
				"w09guj3OGZoaIQl_nalVH"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1724916934752,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 3,
			"text": "Loans",
			"rawText": "Loans",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "e-nlqIpQDujQMsdxMclbA",
			"originalText": "Loans",
			"lineHeight": 1.2,
			"baseline": 15
		},
		{
			"type": "rectangle",
			"version": 152,
			"versionNonce": 2003185202,
			"isDeleted": false,
			"id": "Yqy2SmGghxKfDRkCC3ODx",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 59.75172060256449,
			"y": 3109.759260000505,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#e7f5ff",
			"width": 126,
			"height": 48,
			"seed": 1350759882,
			"groupIds": [
				"w09guj3OGZoaIQl_nalVH"
			],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"type": "text",
					"id": "3uUniQNK"
				}
			],
			"updated": 1724916934752,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 150,
			"versionNonce": 1006667246,
			"isDeleted": false,
			"id": "3uUniQNK",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 99.31422060256449,
			"y": 3124.159260000505,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#e7f5ff",
			"width": 46.875,
			"height": 19.2,
			"seed": 620080266,
			"groupIds": [
				"w09guj3OGZoaIQl_nalVH"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1724916934752,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 3,
			"text": "Cards",
			"rawText": "Cards",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "Yqy2SmGghxKfDRkCC3ODx",
			"originalText": "Cards",
			"lineHeight": 1.2,
			"baseline": 15
		},
		{
			"type": "rectangle",
			"version": 104,
			"versionNonce": 1722128370,
			"isDeleted": false,
			"id": "aRQ_R1PQ2YfQ5gg-39fcb",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 11.154086371258302,
			"y": 2949.3655641893038,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 265.9835125001674,
			"height": 242.90798899982883,
			"seed": 942930390,
			"groupIds": [
				"w09guj3OGZoaIQl_nalVH"
			],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [],
			"updated": 1724916934752,
			"link": null,
			"locked": false
		},
		{
			"type": "diamond",
			"version": 166,
			"versionNonce": 1914017838,
			"isDeleted": false,
			"id": "QAjVDi_Cnb_1Cc9NdIcEp",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 343.4812586987,
			"y": 3023.5932262765014,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ebfbee",
			"width": 204,
			"height": 98,
			"seed": 2016049546,
			"groupIds": [
				"w09guj3OGZoaIQl_nalVH"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [
				{
					"type": "text",
					"id": "l6YWMVcJ"
				}
			],
			"updated": 1724916934752,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 143,
			"versionNonce": 366070194,
			"isDeleted": false,
			"id": "l6YWMVcJ",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 412.6687586987,
			"y": 3053.3932262765015,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 65.625,
			"height": 38.4,
			"seed": 738740746,
			"groupIds": [
				"w09guj3OGZoaIQl_nalVH"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1724916934752,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 3,
			"text": "Message\nBroker",
			"rawText": "Message\nBroker",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "QAjVDi_Cnb_1Cc9NdIcEp",
			"originalText": "Message\nBroker",
			"lineHeight": 1.2,
			"baseline": 34
		},
		{
			"type": "rectangle",
			"version": 230,
			"versionNonce": 1078878830,
			"isDeleted": false,
			"id": "rEmzSqVke2prlMGhlYlFF",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 619.0104530596416,
			"y": 3044.7653577841443,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#e7f5ff",
			"width": 145,
			"height": 49,
			"seed": 1842266826,
			"groupIds": [
				"w09guj3OGZoaIQl_nalVH"
			],
			"frameId": null,
			"roundness": {
				"type": 3
			},
			"boundElements": [
				{
					"type": "text",
					"id": "RNAbJ7JV"
				}
			],
			"updated": 1724916934752,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 251,
			"versionNonce": 2081538930,
			"isDeleted": false,
			"id": "RNAbJ7JV",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 630.5729530596416,
			"y": 3059.6653577841444,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#e7f5ff",
			"width": 121.875,
			"height": 19.2,
			"seed": 557832586,
			"groupIds": [
				"w09guj3OGZoaIQl_nalVH"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1724916934752,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 3,
			"text": "Config Server",
			"rawText": "Config Server",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "rEmzSqVke2prlMGhlYlFF",
			"originalText": "Config Server",
			"lineHeight": 1.2,
			"baseline": 15
		},
		{
			"type": "text",
			"version": 133,
			"versionNonce": 1500767406,
			"isDeleted": false,
			"id": "uIh647wL",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 645.770291413324,
			"y": 3223.137287775254,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 103.125,
			"height": 38.4,
			"seed": 570102934,
			"groupIds": [
				"w09guj3OGZoaIQl_nalVH"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1724916934752,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 3,
			"text": "github\nconfig repo",
			"rawText": "github\nconfig repo",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "github\nconfig repo",
			"lineHeight": 1.2,
			"baseline": 34
		},
		{
			"type": "ellipse",
			"version": 104,
			"versionNonce": 330073394,
			"isDeleted": false,
			"id": "QnwgQFGskZhZHsE_FW58-",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 636.3032148964801,
			"y": 3185.8573454238995,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec9922",
			"width": 119.3490725848378,
			"height": 118.50456776830698,
			"seed": 1690875082,
			"groupIds": [
				"w09guj3OGZoaIQl_nalVH"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1724916934752,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 534,
			"versionNonce": 791617262,
			"isDeleted": false,
			"id": "HgZgASPns_7FmWKHUU09S",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 728.1176880976961,
			"y": 3176.0674913894227,
			"strokeColor": "#000000",
			"backgroundColor": "#868e96",
			"width": 73.18927959040207,
			"height": 73.18927959040207,
			"seed": 725675734,
			"groupIds": [
				"95GSWjDwhmYRZrKEE-Q0i",
				"w09guj3OGZoaIQl_nalVH"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1724916934752,
			"link": null,
			"locked": false
		},
		{
			"type": "line",
			"version": 4058,
			"versionNonce": 1980305138,
			"isDeleted": false,
			"id": "CBVc17XpGOZdKkfGRAeLa",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 750.3326437329963,
			"y": 3190.749854140036,
			"strokeColor": "#000000",
			"backgroundColor": "#fff",
			"width": 39.64365593455812,
			"height": 45.78695356234746,
			"seed": 1244177430,
			"groupIds": [
				"95GSWjDwhmYRZrKEE-Q0i",
				"w09guj3OGZoaIQl_nalVH"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1724916934752,
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
					3.5582598497359608,
					1.2522120608738647
				],
				[
					5.956217574558001,
					3.824182616294239
				],
				[
					9.224062623438297,
					2.7500930301007616
				],
				[
					18.34261239282744,
					2.874161669677112
				],
				[
					21.18670967737515,
					3.154837980266286
				],
				[
					23.386533939931187,
					1.4024125431366117
				],
				[
					26.441996202204436,
					-0.7184311653483793
				],
				[
					27.279992181308955,
					2.199088065967523
				],
				[
					27.20263870631466,
					5.031246965798097
				],
				[
					30.000256051940408,
					7.712855116601167
				],
				[
					31.250803897680935,
					15.38955703742984
				],
				[
					30.270993214420322,
					23.429494324195776
				],
				[
					27.42180688546509,
					26.553234806336704
				],
				[
					23.541240889919727,
					28.22653361769345
				],
				[
					19.351260994397304,
					29.151010900484422
				],
				[
					20.45999413598173,
					30.1927671528081
				],
				[
					21.71054198172225,
					32.50251965164684
				],
				[
					21.96838689836975,
					39.74746086098854
				],
				[
					21.916817915040266,
					44.1339043924881
				],
				[
					20.55023985680837,
					44.89307357809885
				],
				[
					10.21388176070039,
					45.06852239699908
				],
				[
					8.921434116004626,
					43.80328819812765
				],
				[
					8.560451232698105,
					38.64256786609981
				],
				[
					6.175385753708414,
					39.30550366303304
				],
				[
					2.2303585290011623,
					39.558050633293306
				],
				[
					-1.4568237790585556,
					37.442969757363514
				],
				[
					-3.7516435372215837,
					33.74947031730694
				],
				[
					-5.982002066222743,
					31.476547584964507
				],
				[
					-8.392852036877184,
					29.877083439982737
				],
				[
					-5.118221595453503,
					30.1927671528081
				],
				[
					-2.7976173456257265,
					31.98164152548503
				],
				[
					-0.16759919582089844,
					34.47554285680526
				],
				[
					3.029677770608515,
					36.032915840076924
				],
				[
					6.575045374512084,
					35.590958642121485
				],
				[
					8.328390807715317,
					34.212473096117485
				],
				[
					8.495990003536196,
					32.04477826805009
				],
				[
					9.437123949299698,
					30.161198781525552
				],
				[
					10.661887303375467,
					29.30885275689709
				],
				[
					6.033571049552261,
					28.119777438588354
				],
				[
					1.6115307290470815,
					26.66151926027178
				],
				[
					-0.6446122916188274,
					23.37688037205821
				],
				[
					-2.3334964956601705,
					15.465270245399545
				],
				[
					-0.9927029290929992,
					8.021247722041343
				],
				[
					0.9411339457635058,
					5.981354653934107
				],
				[
					-0.16759919582089844,
					3.212507630050968
				],
				[
					0,
					0
				]
			]
		},
		{
			"type": "text",
			"version": 132,
			"versionNonce": 369692974,
			"isDeleted": false,
			"id": "5QVfZRuv",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 498.3217792874649,
			"y": 3218.7220238545933,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec9922",
			"width": 120.9849853515625,
			"height": 19.2,
			"seed": 793311114,
			"groupIds": [
				"w09guj3OGZoaIQl_nalVH"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1724916934752,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 3,
			"text": "1.변경사항 push",
			"rawText": "1.변경사항 push",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "1.변경사항 push",
			"lineHeight": 1.2,
			"baseline": 15
		},
		{
			"type": "ellipse",
			"version": 166,
			"versionNonce": 2007916722,
			"isDeleted": false,
			"id": "ReWCGTUC5OGAAFcULAwYM",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 443.11956805195854,
			"y": 3215.1081518919627,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#1e1e1e",
			"width": 33.35920827821246,
			"height": 33.35920827821246,
			"seed": 1610355990,
			"groupIds": [
				"zLIWqk7byBezzfUWRziQa",
				"w09guj3OGZoaIQl_nalVH"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1724916934752,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 238,
			"versionNonce": 1768602478,
			"isDeleted": false,
			"id": "DUls90jtamranB0lnrBJ-",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 432.83081117308456,
			"y": 3251.8301631332974,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#1e1e1e",
			"width": 53.93672203596043,
			"height": 14.899296688041431,
			"seed": 1332997654,
			"groupIds": [
				"zLIWqk7byBezzfUWRziQa",
				"w09guj3OGZoaIQl_nalVH"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1724916934752,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 153,
			"versionNonce": 1145272946,
			"isDeleted": false,
			"id": "rZpwsBicpv2WWBL6XHQ7n",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 432.51634091107314,
			"y": 3259.8897316225903,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#1e1e1e",
			"width": 54.56566255998325,
			"height": 19.55548540621112,
			"seed": 444487562,
			"groupIds": [
				"zLIWqk7byBezzfUWRziQa",
				"w09guj3OGZoaIQl_nalVH"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1724916934753,
			"link": null,
			"locked": false
		},
		{
			"type": "line",
			"version": 474,
			"versionNonce": 798825902,
			"isDeleted": false,
			"id": "IQ7e4kI8CqdGAhwXXqxFT",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 514.1546227012783,
			"y": 3254.344834356912,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 98.18517087809278,
			"height": 19.32855864780592,
			"seed": 1763018698,
			"groupIds": [
				"w09guj3OGZoaIQl_nalVH"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1724916934753,
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
					79.4640903208724,
					0.15774231596634536
				],
				[
					79.35469572532202,
					10.230909457901106
				],
				[
					98.18517087809278,
					0.7964282850563222
				],
				[
					79.59091164343863,
					-9.097649189904814
				],
				[
					79.42277379498182,
					-0.056396254016533476
				]
			]
		},
		{
			"type": "line",
			"version": 718,
			"versionNonce": 2056215602,
			"isDeleted": false,
			"id": "6ScbCvlqv-hJj1p5gPMq2",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 4.71238898038469,
			"x": 667.5208685982344,
			"y": 3136.970724342226,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 54.97368654875936,
			"height": 19.32855864780592,
			"seed": 580859862,
			"groupIds": [
				"w09guj3OGZoaIQl_nalVH"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1724916934753,
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
					36.252605991538985,
					6.659495683243256e-15
				],
				[
					36.1432113959886,
					10.073167141934766
				],
				[
					54.97368654875936,
					0.6386859690899833
				],
				[
					36.379427314105214,
					-9.255391505871154
				],
				[
					36.211289465648406,
					-0.21413856998287217
				]
			]
		},
		{
			"type": "line",
			"version": 758,
			"versionNonce": 1036597230,
			"isDeleted": false,
			"id": "CyoOKuSoiouC_NOnL4bWv",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 3.141592653589793,
			"x": 556.0639851696831,
			"y": 3072.913752714778,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 54.97368654875936,
			"height": 19.32855864780592,
			"seed": 1832291926,
			"groupIds": [
				"w09guj3OGZoaIQl_nalVH"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1724916934753,
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
					36.252605991538985,
					6.659495683243256e-15
				],
				[
					36.1432113959886,
					10.073167141934766
				],
				[
					54.97368654875936,
					0.6386859690899833
				],
				[
					36.379427314105214,
					-9.255391505871154
				],
				[
					36.211289465648406,
					-0.21413856998287217
				]
			]
		},
		{
			"type": "line",
			"version": 815,
			"versionNonce": 1215890930,
			"isDeleted": false,
			"id": "CLQWJiFvuWrR_0pBR0y7Z",
			"fillStyle": "hachure",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 3.141592653589793,
			"x": 285.79201127385966,
			"y": 3075.117580599358,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 54.97368654875936,
			"height": 19.32855864780592,
			"seed": 1790700630,
			"groupIds": [
				"w09guj3OGZoaIQl_nalVH"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1724916934753,
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
					36.252605991538985,
					6.659495683243256e-15
				],
				[
					36.1432113959886,
					10.073167141934766
				],
				[
					54.97368654875936,
					0.6386859690899833
				],
				[
					36.379427314105214,
					-9.255391505871154
				],
				[
					36.211289465648406,
					-0.21413856998287217
				]
			]
		},
		{
			"type": "text",
			"version": 315,
			"versionNonce": 1542982190,
			"isDeleted": false,
			"id": "jqMdHtCo",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 716.5337085173961,
			"y": 3113.721924999278,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#1e1e1e",
			"width": 371.88494873046875,
			"height": 38.4,
			"seed": 1723211402,
			"groupIds": [
				"w09guj3OGZoaIQl_nalVH"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1724916934753,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 3,
			"text": "2.`domain/actuator/busrefresh` 호출\n  - config 서버가 repo에서 최신 데이터를 받아옴",
			"rawText": "2.`domain/actuator/busrefresh` 호출\n  - config 서버가 repo에서 최신 데이터를 받아옴",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "2.`domain/actuator/busrefresh` 호출\n  - config 서버가 repo에서 최신 데이터를 받아옴",
			"lineHeight": 1.2,
			"baseline": 34
		},
		{
			"type": "text",
			"version": 513,
			"versionNonce": 117929906,
			"isDeleted": false,
			"id": "3wH4kL4w",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 342.825369874678,
			"y": 3128.7611428010223,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#1e1e1e",
			"width": 217.86495971679688,
			"height": 38.4,
			"seed": 683426378,
			"groupIds": [
				"w09guj3OGZoaIQl_nalVH"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1724916934753,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 3,
			"text": "3.설정이 바뀐 이벤트를 감지\n  - 구독 중인 노드를 새로고침",
			"rawText": "3.설정이 바뀐 이벤트를 감지\n  - 구독 중인 노드를 새로고침",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "3.설정이 바뀐 이벤트를 감지\n  - 구독 중인 노드를 새로고침",
			"lineHeight": 1.2,
			"baseline": 34
		},
		{
			"type": "line",
			"version": 670,
			"versionNonce": 1762825326,
			"isDeleted": false,
			"id": "PnYuG3DL-W2WcTe2kUXtb",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 220.90448459737172,
			"y": 2939.4459329161814,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ebfbee",
			"width": 483.30991747393705,
			"height": 141.6726571118993,
			"seed": 908949462,
			"groupIds": [
				"w09guj3OGZoaIQl_nalVH"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1724916934753,
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
					2.842170943040401e-14,
					-49.04975272228239
				],
				[
					472.3723742986689,
					-49.04975272228239
				],
				[
					472.3723742986689,
					74.20230158219738
				],
				[
					460.55560118805613,
					74.20230158219738
				],
				[
					472.7946267069343,
					92.6229043896169
				],
				[
					483.30991747393705,
					74.40988652480837
				],
				[
					472.39964747012493,
					74.20796673399309
				]
			]
		},
		{
			"type": "text",
			"version": 149,
			"versionNonce": 1449242994,
			"isDeleted": false,
			"id": "hb7jEoPE",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 298.81781136051563,
			"y": 2862.4074381617975,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ebfbee",
			"width": 329.4749450683594,
			"height": 19.2,
			"seed": 1631186698,
			"groupIds": [
				"w09guj3OGZoaIQl_nalVH"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1724916934753,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 3,
			"text": "4.새 설정 데이터를 config 서버에서 받아온다",
			"rawText": "4.새 설정 데이터를 config 서버에서 받아온다",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "4.새 설정 데이터를 config 서버에서 받아온다",
			"lineHeight": 1.2,
			"baseline": 15
		},
		{
			"type": "image",
			"version": 66,
			"versionNonce": 2128729774,
			"isDeleted": false,
			"id": "w3L3v5ngtJ9BGZYJCDoAz",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1733.4217911657643,
			"y": -137.3783629916124,
			"strokeColor": "transparent",
			"backgroundColor": "#ebfbee",
			"width": 1440,
			"height": 335,
			"seed": 1508569814,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1724916934753,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "5a834bd01d55ddb7a9b46fe579531fc6916cc3b8",
			"scale": [
				1,
				1
			]
		},
		{
			"type": "image",
			"version": 138,
			"versionNonce": 969847602,
			"isDeleted": false,
			"id": "cyc3BheUWFliD_ic1qTtC",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2271.7211371062613,
			"y": 462.3839893484791,
			"strokeColor": "transparent",
			"backgroundColor": "#ebfbee",
			"width": 565.3282121810103,
			"height": 376.2488439177669,
			"seed": 2141109757,
			"groupIds": [
				"H8X5mlrrdGvyt6Fd6dCnA"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1724916934753,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "2cf2d4ed94e24c697d4cca078a3e8f28b6540573",
			"scale": [
				1,
				1
			]
		},
		{
			"type": "rectangle",
			"version": 160,
			"versionNonce": 370069742,
			"isDeleted": false,
			"id": "VI_BsC3SeF0PGmLgsCzBa",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2309.5549731684982,
			"y": 471.6751551840579,
			"strokeColor": "#e03131",
			"backgroundColor": "transparent",
			"width": 507.39274324567623,
			"height": 111.85343338791705,
			"seed": 677495027,
			"groupIds": [
				"H8X5mlrrdGvyt6Fd6dCnA"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1724916934753,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 276,
			"versionNonce": 867532018,
			"isDeleted": false,
			"id": "1cgCh2pB",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2730.1087896595864,
			"y": 562.1224617775019,
			"strokeColor": "#ffc9c9",
			"backgroundColor": "transparent",
			"width": 83.4849853515625,
			"height": 19.2,
			"seed": 222330707,
			"groupIds": [
				"H8X5mlrrdGvyt6Fd6dCnA"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1724916934753,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 3,
			"text": "10번째 요청",
			"rawText": "10번째 요청",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "10번째 요청",
			"lineHeight": 1.2,
			"baseline": 15
		},
		{
			"type": "rectangle",
			"version": 248,
			"versionNonce": 706904878,
			"isDeleted": false,
			"id": "ODmmv6fzemcZy4R3US_Nd",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2309.5549731684982,
			"y": 597.4912428956991,
			"strokeColor": "#e03131",
			"backgroundColor": "transparent",
			"width": 507.39274324567623,
			"height": 111.85343338791705,
			"seed": 405306653,
			"groupIds": [
				"H8X5mlrrdGvyt6Fd6dCnA"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1724916934753,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 337,
			"versionNonce": 1637682866,
			"isDeleted": false,
			"id": "FJmdFqxf2oDAgvsSbEXhE",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2309.5549731684982,
			"y": 723.3073306073403,
			"strokeColor": "#e03131",
			"backgroundColor": "transparent",
			"width": 507.39274324567623,
			"height": 111.85343338791705,
			"seed": 1507650045,
			"groupIds": [
				"H8X5mlrrdGvyt6Fd6dCnA"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1724916934753,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 192,
			"versionNonce": 1569058158,
			"isDeleted": false,
			"id": "9GO4Yh6B",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2687.7975237811315,
			"y": 685.8727678854402,
			"strokeColor": "#ffc9c9",
			"backgroundColor": "transparent",
			"width": 125.44998168945312,
			"height": 19.2,
			"seed": 69985235,
			"groupIds": [
				"H8X5mlrrdGvyt6Fd6dCnA"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1724916934753,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 3,
			"text": "OPEN 상태로 전환",
			"rawText": "OPEN 상태로 전환",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "OPEN 상태로 전환",
			"lineHeight": 1.2,
			"baseline": 15
		},
		{
			"type": "text",
			"version": 363,
			"versionNonce": 405563506,
			"isDeleted": false,
			"id": "myGnR4rR",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2576.651119474934,
			"y": 807.4491070185087,
			"strokeColor": "#ffc9c9",
			"backgroundColor": "transparent",
			"width": 231.00294494628906,
			"height": 19.2,
			"seed": 232395443,
			"groupIds": [
				"H8X5mlrrdGvyt6Fd6dCnA"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1724916934753,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 3,
			"text": "\b회로 차단 패턴에 의해 요청 차단",
			"rawText": "\b회로 차단 패턴에 의해 요청 차단",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "\b회로 차단 패턴에 의해 요청 차단",
			"lineHeight": 1.2,
			"baseline": 15
		},
		{
			"type": "image",
			"version": 27,
			"versionNonce": 495062958,
			"isDeleted": false,
			"id": "ZpXxdObJDOaDAsEcN895w",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2079.030457859421,
			"y": 1148.7775776175883,
			"strokeColor": "transparent",
			"backgroundColor": "transparent",
			"width": 588,
			"height": 559,
			"seed": 982252394,
			"groupIds": [],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1724916934753,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "1bd6f6c757e9a6fa30092af5f7b5e298ef45ce8f",
			"scale": [
				1,
				1
			]
		},
		{
			"type": "text",
			"version": 94,
			"versionNonce": 2133494322,
			"isDeleted": false,
			"id": "t4YEYIjY",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1960.2754442729997,
			"y": 1962.8658316879707,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 56.25,
			"height": 19.2,
			"seed": 178291246,
			"groupIds": [
				"UqDNS8ubT-b8auhYxi4dj",
				"WYN-t9e5XbqvO5zSsrft7"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1724916934753,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 3,
			"text": "Client",
			"rawText": "Client",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Client",
			"lineHeight": 1.2,
			"baseline": 15
		},
		{
			"type": "line",
			"version": 55,
			"versionNonce": 1178593774,
			"isDeleted": false,
			"id": "RPiYEvaK9yB3MD4DI2Jbx",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1988.4004442729997,
			"y": 2000.749135431866,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 0,
			"height": 436.78855716536054,
			"seed": 1668609390,
			"groupIds": [
				"UqDNS8ubT-b8auhYxi4dj",
				"WYN-t9e5XbqvO5zSsrft7"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1724916934753,
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
					0,
					436.78855716536054
				]
			]
		},
		{
			"type": "text",
			"version": 134,
			"versionNonce": 763261938,
			"isDeleted": false,
			"id": "BdzaVV04",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2158.1784896110735,
			"y": 1962.8658316879707,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 103.125,
			"height": 19.2,
			"seed": 610335598,
			"groupIds": [
				"tYUalaql54WMZAB7EqtxJ",
				"WYN-t9e5XbqvO5zSsrft7"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1724916934753,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 3,
			"text": "Auth Server",
			"rawText": "Auth Server",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Auth Server",
			"lineHeight": 1.2,
			"baseline": 15
		},
		{
			"type": "line",
			"version": 91,
			"versionNonce": 1187544110,
			"isDeleted": false,
			"id": "89VDvRFKEx1Y-4gmUBSir",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2209.7409896110735,
			"y": 2000.7491354318659,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 0,
			"height": 436.78855716536054,
			"seed": 2101294766,
			"groupIds": [
				"tYUalaql54WMZAB7EqtxJ",
				"WYN-t9e5XbqvO5zSsrft7"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1724916934753,
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
					0,
					436.78855716536054
				]
			]
		},
		{
			"type": "text",
			"version": 167,
			"versionNonce": 1160717746,
			"isDeleted": false,
			"id": "7MVg015V",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2402.956534949147,
			"y": 1962.8658316879707,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 140.625,
			"height": 19.2,
			"seed": 894098414,
			"groupIds": [
				"W4DvSp5r2_OAAlrm-8qaU",
				"WYN-t9e5XbqvO5zSsrft7"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1724916934753,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 3,
			"text": "Resource Server",
			"rawText": "Resource Server",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Resource Server",
			"lineHeight": 1.2,
			"baseline": 15
		},
		{
			"type": "line",
			"version": 107,
			"versionNonce": 1157940846,
			"isDeleted": false,
			"id": "Opf-auppdGrnRDciE3Qzf",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2473.269034949147,
			"y": 2000.749135431866,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 0,
			"height": 436.78855716536054,
			"seed": 971294510,
			"groupIds": [
				"W4DvSp5r2_OAAlrm-8qaU",
				"WYN-t9e5XbqvO5zSsrft7"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1724916934753,
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
					0,
					436.78855716536054
				]
			]
		},
		{
			"type": "text",
			"version": 333,
			"versionNonce": 258187122,
			"isDeleted": false,
			"id": "qHdsn2uW",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2000.0316349811528,
			"y": 2025.6444711405436,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 200.5035400390625,
			"height": 24.135524289400205,
			"seed": 1735591726,
			"groupIds": [
				"WYN-t9e5XbqvO5zSsrft7"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1724916934753,
			"link": null,
			"locked": false,
			"fontSize": 10.056468453916752,
			"fontFamily": 3,
			"text": "리소스 서버의 보호된 자원에 접근하려고 한다.\nclient credential을 제공한다.",
			"rawText": "리소스 서버의 보호된 자원에 접근하려고 한다.\nclient credential을 제공한다.",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "리소스 서버의 보호된 자원에 접근하려고 한다.\nclient credential을 제공한다.",
			"lineHeight": 1.2,
			"baseline": 22
		},
		{
			"type": "arrow",
			"version": 61,
			"versionNonce": 1102956718,
			"isDeleted": false,
			"id": "lW0k2amNBa7krmI1K_neF",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1987.7516050180732,
			"y": 2070.63166910379,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 216.90986302480428,
			"height": 0,
			"seed": 430290098,
			"groupIds": [
				"WYN-t9e5XbqvO5zSsrft7"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1724916934753,
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
					216.90986302480428,
					0
				]
			]
		},
		{
			"type": "text",
			"version": 459,
			"versionNonce": 409133362,
			"isDeleted": false,
			"id": "Q4wfjRoP",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2012.0502388686978,
			"y": 2131.4490208241177,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 181.151123046875,
			"height": 24.135524289400205,
			"seed": 553702190,
			"groupIds": [
				"WYN-t9e5XbqvO5zSsrft7"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1724916934753,
			"link": null,
			"locked": false,
			"fontSize": 10.056468453916752,
			"fontFamily": 3,
			"text": "client credential이 유효하다.\n접근 가능한 Access token을 발급한다.",
			"rawText": "client credential이 유효하다.\n접근 가능한 Access token을 발급한다.",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "client credential이 유효하다.\n접근 가능한 Access token을 발급한다.",
			"lineHeight": 1.2,
			"baseline": 22
		},
		{
			"type": "arrow",
			"version": 60,
			"versionNonce": 1016890094,
			"isDeleted": false,
			"id": "uaSVKl_wIkgv0S_9laToC",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2207.8731486121906,
			"y": 2172.0060288506706,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 216.45755640398443,
			"height": 0,
			"seed": 834076978,
			"groupIds": [
				"WYN-t9e5XbqvO5zSsrft7"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1724916934753,
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
					-216.45755640398443,
					0
				]
			]
		},
		{
			"type": "arrow",
			"version": 831,
			"versionNonce": 1267985138,
			"isDeleted": false,
			"id": "68FjqBy8dtiEvk09Qr_eD",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1988.8717469179564,
			"y": 2253.9858449705766,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 478.9441416099435,
			"height": 0,
			"seed": 1017767730,
			"groupIds": [
				"WYN-t9e5XbqvO5zSsrft7"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1724916934753,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "AeOYRTWq",
				"focus": 2.114507941410512,
				"gap": 13.449616745321464
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
					478.9441416099435,
					0
				]
			]
		},
		{
			"type": "text",
			"version": 678,
			"versionNonce": 1479144750,
			"isDeleted": false,
			"id": "AeOYRTWq",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1998.8023592786171,
			"y": 2216.400703935855,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 269.20166015625,
			"height": 24.135524289400205,
			"seed": 1469708978,
			"groupIds": [
				"WYN-t9e5XbqvO5zSsrft7"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "68FjqBy8dtiEvk09Qr_eD",
					"type": "arrow"
				}
			],
			"updated": 1724916934753,
			"link": null,
			"locked": false,
			"fontSize": 10.056468453916752,
			"fontFamily": 3,
			"text": "보호된 자원에 접근하려고 한다.\nAuth server로 부터 발급받은 Access Token을 제공한다.",
			"rawText": "보호된 자원에 접근하려고 한다.\nAuth server로 부터 발급받은 Access Token을 제공한다.",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "보호된 자원에 접근하려고 한다.\nAuth server로 부터 발급받은 Access Token을 제공한다.",
			"lineHeight": 1.2,
			"baseline": 22
		},
		{
			"type": "arrow",
			"version": 800,
			"versionNonce": 259898546,
			"isDeleted": false,
			"id": "oV5h2OZ_pfmHKDepBZU_3",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2474.272641430479,
			"y": 2365.459695505835,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 483.1090052593738,
			"height": 0,
			"seed": 1801164210,
			"groupIds": [
				"WYN-t9e5XbqvO5zSsrft7"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1724916934753,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "qULRLDKM",
				"focus": -1.7339166357534013,
				"gap": 8.8567313943106
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
					-483.1090052593738,
					0
				]
			]
		},
		{
			"type": "text",
			"version": 973,
			"versionNonce": 2110725998,
			"isDeleted": false,
			"id": "qULRLDKM",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2342.652785188899,
			"y": 2332.4674398221246,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 124.7894287109375,
			"height": 24.135524289400205,
			"seed": 1974751342,
			"groupIds": [
				"WYN-t9e5XbqvO5zSsrft7"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"id": "oV5h2OZ_pfmHKDepBZU_3",
					"type": "arrow"
				}
			],
			"updated": 1724916934753,
			"link": null,
			"locked": false,
			"fontSize": 10.056468453916752,
			"fontFamily": 3,
			"text": "토큰이 유효함을 확인했으므로\n요청한 리소스를 제공한다.",
			"rawText": "토큰이 유효함을 확인했으므로\n요청한 리소스를 제공한다.",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "토큰이 유효함을 확인했으므로\n요청한 리소스를 제공한다.",
			"lineHeight": 1.2,
			"baseline": 22
		},
		{
			"type": "text",
			"version": 172,
			"versionNonce": 1640453746,
			"isDeleted": false,
			"id": "sEGqCsXr",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2073.9965035795253,
			"y": 2772.880649896842,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 56.25,
			"height": 19.2,
			"seed": 1222454898,
			"groupIds": [
				"_zMf-1lkSSchbk52VFmO6",
				"WLksZQtdcYjFrMDoiwTCq"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1724916934754,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 3,
			"text": "Client",
			"rawText": "Client",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Client",
			"lineHeight": 1.2,
			"baseline": 15
		},
		{
			"type": "line",
			"version": 196,
			"versionNonce": 30736814,
			"isDeleted": false,
			"id": "rQPaPYrgFY9k2PG695Kk7",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2102.1215035795253,
			"y": 2810.7639536407373,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 0,
			"height": 868.4575363718436,
			"seed": 701665330,
			"groupIds": [
				"_zMf-1lkSSchbk52VFmO6",
				"WLksZQtdcYjFrMDoiwTCq"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1724916934754,
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
					0,
					868.4575363718436
				]
			]
		},
		{
			"type": "text",
			"version": 258,
			"versionNonce": 1933031474,
			"isDeleted": false,
			"id": "V5eRkDtA",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2379.8613207755498,
			"y": 2772.880649896842,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 103.125,
			"height": 19.2,
			"seed": 288733682,
			"groupIds": [
				"iR0-IW4s6UKUF-5-yW4bJ",
				"WLksZQtdcYjFrMDoiwTCq"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1724916934754,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 3,
			"text": "Auth Server",
			"rawText": "Auth Server",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Auth Server",
			"lineHeight": 1.2,
			"baseline": 15
		},
		{
			"type": "line",
			"version": 262,
			"versionNonce": 1197775854,
			"isDeleted": false,
			"id": "YO1-j5DmWtNNp3p7n9ljF",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2431.4238207755498,
			"y": 2810.7639536407373,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 0,
			"height": 876.5512863718432,
			"seed": 2114825138,
			"groupIds": [
				"iR0-IW4s6UKUF-5-yW4bJ",
				"WLksZQtdcYjFrMDoiwTCq"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1724916934754,
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
					0,
					876.5512863718432
				]
			]
		},
		{
			"type": "text",
			"version": 349,
			"versionNonce": 1135993330,
			"isDeleted": false,
			"id": "aigmTlIa",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2732.6063463049077,
			"y": 2772.2452332301755,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 140.625,
			"height": 19.2,
			"seed": 1988191602,
			"groupIds": [
				"yx7QmyqDL6pv61lEAXc_e",
				"WLksZQtdcYjFrMDoiwTCq"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1724916934754,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 3,
			"text": "Resource Server",
			"rawText": "Resource Server",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Resource Server",
			"lineHeight": 1.2,
			"baseline": 15
		},
		{
			"type": "line",
			"version": 362,
			"versionNonce": 1686564398,
			"isDeleted": false,
			"id": "Exm2gvDgycO7PbvRB8VNe",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2802.9188463049077,
			"y": 2810.128536974071,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 0,
			"height": 871.4679530385097,
			"seed": 601351986,
			"groupIds": [
				"yx7QmyqDL6pv61lEAXc_e",
				"WLksZQtdcYjFrMDoiwTCq"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1724916934754,
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
					0,
					871.4679530385097
				]
			]
		},
		{
			"type": "text",
			"version": 403,
			"versionNonce": 1044960178,
			"isDeleted": false,
			"id": "lBKxoWmz",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1786.881686383501,
			"y": 2772.880649896842,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 37.5,
			"height": 19.2,
			"seed": 1457984754,
			"groupIds": [
				"ACvQRNYS3aes88JbAlmwq",
				"WLksZQtdcYjFrMDoiwTCq"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1724916934754,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 3,
			"text": "User",
			"rawText": "User",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "User",
			"lineHeight": 1.2,
			"baseline": 15
		},
		{
			"type": "line",
			"version": 424,
			"versionNonce": 1176828014,
			"isDeleted": false,
			"id": "DlN2I419vp1kLvtYGUFHo",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1805.631686383501,
			"y": 2811.0022348907373,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 0,
			"height": 867.8025884551766,
			"seed": 1524344498,
			"groupIds": [
				"ACvQRNYS3aes88JbAlmwq",
				"WLksZQtdcYjFrMDoiwTCq"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1724916934754,
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
					0,
					867.8025884551766
				]
			]
		},
		{
			"id": "TWPfSIE0",
			"type": "text",
			"x": 1842.8435746357368,
			"y": 2845.6503551441556,
			"width": 195.53997802734375,
			"height": 19.2,
			"angle": 0,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"groupIds": [
				"WLksZQtdcYjFrMDoiwTCq"
			],
			"frameId": null,
			"roundness": null,
			"seed": 153756910,
			"version": 346,
			"versionNonce": 1427606898,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1724916934754,
			"link": null,
			"locked": false,
			"text": "1.resource에 접근할 거야",
			"rawText": "1.resource에 접근할 거야",
			"fontSize": 16,
			"fontFamily": 3,
			"textAlign": "left",
			"verticalAlign": "top",
			"baseline": 15,
			"containerId": null,
			"originalText": "1.resource에 접근할 거야",
			"lineHeight": 1.2
		},
		{
			"type": "text",
			"version": 453,
			"versionNonce": 1409792686,
			"isDeleted": false,
			"id": "gux8RUHb",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1850.7365205778624,
			"y": 2912.473052512576,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 208.93496704101562,
			"height": 38.4,
			"seed": 496343218,
			"groupIds": [
				"WLksZQtdcYjFrMDoiwTCq"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1724916934754,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 3,
			"text": "2.auth 서버에서 다음 작업을\n수행해",
			"rawText": "2.auth 서버에서 다음 작업을\n수행해",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "2.auth 서버에서 다음 작업을\n수행해",
			"lineHeight": 1.2,
			"baseline": 34
		},
		{
			"id": "HB6Z87jL",
			"type": "text",
			"x": 1858.8405592848599,
			"y": 2999.328809091523,
			"width": 493.31494140625,
			"height": 19.2,
			"angle": 0,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"groupIds": [
				"WLksZQtdcYjFrMDoiwTCq"
			],
			"frameId": null,
			"roundness": null,
			"seed": 196616242,
			"version": 638,
			"versionNonce": 493424434,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1724916934754,
			"link": null,
			"locked": false,
			"text": "3.ID/PW 줄테니 client 한테 내 resource에 접근해도 된다고 해줘",
			"rawText": "3.ID/PW 줄테니 client 한테 내 resource에 접근해도 된다고 해줘",
			"fontSize": 16,
			"fontFamily": 3,
			"textAlign": "left",
			"verticalAlign": "top",
			"baseline": 15,
			"containerId": null,
			"originalText": "3.ID/PW 줄테니 client 한테 내 resource에 접근해도 된다고 해줘",
			"lineHeight": 1.2
		},
		{
			"id": "I3hc1agG",
			"type": "text",
			"x": 2117.201579021702,
			"y": 3082.851561284507,
			"width": 395.9899597167969,
			"height": 19.2,
			"angle": 0,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"groupIds": [
				"WLksZQtdcYjFrMDoiwTCq"
			],
			"frameId": null,
			"roundness": null,
			"seed": 2014928622,
			"version": 498,
			"versionNonce": 349713646,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1724916934754,
			"link": null,
			"locked": false,
			"text": "4.유저 확인 됐으니 AUTHORIZATION CODE(임시) 줄게",
			"rawText": "4.유저 확인 됐으니 AUTHORIZATION CODE(임시) 줄게",
			"fontSize": 16,
			"fontFamily": 3,
			"textAlign": "left",
			"verticalAlign": "top",
			"baseline": 15,
			"containerId": null,
			"originalText": "4.유저 확인 됐으니 AUTHORIZATION CODE(임시) 줄게",
			"lineHeight": 1.2
		},
		{
			"id": "41uXrYNQ",
			"type": "text",
			"x": 2114.834254460297,
			"y": 3170.579905582757,
			"width": 312.9499816894531,
			"height": 38.4,
			"angle": 0,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"groupIds": [
				"WLksZQtdcYjFrMDoiwTCq"
			],
			"frameId": null,
			"roundness": null,
			"seed": 1572576750,
			"version": 531,
			"versionNonce": 1805932786,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1724916934754,
			"link": null,
			"locked": false,
			"text": "5. 여기 내 credentials와 AUTH CODE야\naccess token을 주겠니?",
			"rawText": "5. 여기 내 credentials와 AUTH CODE야\naccess token을 주겠니?",
			"fontSize": 16,
			"fontFamily": 3,
			"textAlign": "left",
			"verticalAlign": "top",
			"baseline": 34,
			"containerId": null,
			"originalText": "5. 여기 내 credentials와 AUTH CODE야\naccess token을 주겠니?",
			"lineHeight": 1.2
		},
		{
			"id": "MYIND59vgWXWVJsj6oGnJ",
			"type": "arrow",
			"x": 1806.8845559953859,
			"y": 2875.1485733459126,
			"width": 288.5624999999998,
			"height": 0,
			"angle": 0,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"groupIds": [
				"WLksZQtdcYjFrMDoiwTCq"
			],
			"frameId": null,
			"roundness": null,
			"seed": 70444274,
			"version": 72,
			"versionNonce": 1377789742,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1724916934754,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					288.5624999999998,
					0
				]
			],
			"lastCommittedPoint": [
				288.5624999999998,
				0
			],
			"startBinding": null,
			"endBinding": null,
			"startArrowhead": null,
			"endArrowhead": "arrow"
		},
		{
			"id": "-8CSBnXayNMYBJGsgUl-x",
			"type": "arrow",
			"x": 2103.738722662052,
			"y": 2958.4141983459126,
			"width": 294.20833333333303,
			"height": 0,
			"angle": 0,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"groupIds": [
				"WLksZQtdcYjFrMDoiwTCq"
			],
			"frameId": null,
			"roundness": null,
			"seed": 2055633970,
			"version": 125,
			"versionNonce": 1867541170,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1724916934754,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					-294.20833333333303,
					0
				]
			],
			"lastCommittedPoint": [
				-294.20833333333303,
				0
			],
			"startBinding": null,
			"endBinding": null,
			"startArrowhead": null,
			"endArrowhead": "arrow"
		},
		{
			"id": "S71xMpgsh9mi7ePFh2LsT",
			"type": "arrow",
			"x": 1807.4939309953857,
			"y": 3046.711073345913,
			"width": 618.5729166666665,
			"height": 0,
			"angle": 0,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"groupIds": [
				"WLksZQtdcYjFrMDoiwTCq"
			],
			"frameId": null,
			"roundness": null,
			"seed": 240349490,
			"version": 66,
			"versionNonce": 1011241326,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1724916934754,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					618.5729166666665,
					0
				]
			],
			"lastCommittedPoint": [
				618.5729166666665,
				0
			],
			"startBinding": null,
			"endBinding": null,
			"startArrowhead": null,
			"endArrowhead": "arrow"
		},
		{
			"id": "gQDz6GnnEsSiIP8xXDl92",
			"type": "arrow",
			"x": 2427.832472662052,
			"y": 3129.7891983459126,
			"width": 312.92708333333303,
			"height": 0,
			"angle": 0,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"groupIds": [
				"WLksZQtdcYjFrMDoiwTCq"
			],
			"frameId": null,
			"roundness": null,
			"seed": 262757426,
			"version": 83,
			"versionNonce": 1326728306,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1724916934754,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					-312.92708333333303,
					0
				]
			],
			"lastCommittedPoint": [
				-312.92708333333303,
				0
			],
			"startBinding": null,
			"endBinding": null,
			"startArrowhead": null,
			"endArrowhead": "arrow"
		},
		{
			"id": "wMSAoJHYOgzi_3QGO87lE",
			"type": "arrow",
			"x": 2102.967889328719,
			"y": 3251.5548233459126,
			"width": 317.88020833333303,
			"height": 0,
			"angle": 0,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"groupIds": [
				"WLksZQtdcYjFrMDoiwTCq"
			],
			"frameId": null,
			"roundness": null,
			"seed": 2105406062,
			"version": 61,
			"versionNonce": 244708270,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1724916934754,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					317.88020833333303,
					0
				]
			],
			"lastCommittedPoint": [
				317.88020833333303,
				0
			],
			"startBinding": null,
			"endBinding": null,
			"startArrowhead": null,
			"endArrowhead": "arrow"
		},
		{
			"id": "au3dftGl",
			"type": "text",
			"x": 2490.223097662053,
			"y": 3298.44024001258,
			"width": 206.25,
			"height": 38.4,
			"angle": 0,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"groupIds": [
				"WLksZQtdcYjFrMDoiwTCq"
			],
			"frameId": null,
			"roundness": null,
			"seed": 1691616690,
			"version": 172,
			"versionNonce": 1152837170,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1724916934754,
			"link": null,
			"locked": false,
			"text": "credentials(ID/SECRET)\nAUTH CODE 유효성 검사",
			"rawText": "credentials(ID/SECRET)\nAUTH CODE 유효성 검사",
			"fontSize": 16,
			"fontFamily": 3,
			"textAlign": "left",
			"verticalAlign": "top",
			"baseline": 34,
			"containerId": null,
			"originalText": "credentials(ID/SECRET)\nAUTH CODE 유효성 검사",
			"lineHeight": 1.2
		},
		{
			"id": "XB4MYqlDv8-PpR-F5rR3E",
			"type": "arrow",
			"x": 2432.74913932872,
			"y": 3278.586073345913,
			"width": 38.578125,
			"height": 80.19270833333348,
			"angle": 0,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"groupIds": [
				"WLksZQtdcYjFrMDoiwTCq"
			],
			"frameId": null,
			"roundness": null,
			"seed": 1112748782,
			"version": 100,
			"versionNonce": 859262446,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1724916934754,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					37.447916666666515,
					0
				],
				[
					37.447916666666515,
					80.19270833333348
				],
				[
					-1.130208333333485,
					80.19270833333348
				]
			],
			"lastCommittedPoint": [
				-1.130208333333485,
				80.19270833333348
			],
			"startBinding": null,
			"endBinding": null,
			"startArrowhead": null,
			"endArrowhead": "arrow"
		},
		{
			"id": "Djhs1R2nv_RJHDHXTvtMA",
			"type": "arrow",
			"x": 2430.10851432872,
			"y": 3402.9037816792465,
			"width": 316.0625,
			"height": 0,
			"angle": 0,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"groupIds": [
				"WLksZQtdcYjFrMDoiwTCq"
			],
			"frameId": null,
			"roundness": null,
			"seed": 1095660338,
			"version": 144,
			"versionNonce": 958353394,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1724916934754,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					-316.0625,
					0
				]
			],
			"lastCommittedPoint": [
				-316.0625,
				0
			],
			"startBinding": null,
			"endBinding": null,
			"startArrowhead": null,
			"endArrowhead": "arrow"
		},
		{
			"id": "Cdg2sAwl",
			"type": "text",
			"x": 2144.1605976620535,
			"y": 3366.5287816792465,
			"width": 250.89996337890625,
			"height": 19.2,
			"angle": 0,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"groupIds": [
				"WLksZQtdcYjFrMDoiwTCq"
			],
			"frameId": null,
			"roundness": null,
			"seed": 1920125426,
			"version": 137,
			"versionNonce": 1731420206,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1724916934754,
			"link": null,
			"locked": false,
			"text": "6.확인 되었으니 access 토큰 줄게",
			"rawText": "6.확인 되었으니 access 토큰 줄게",
			"fontSize": 16,
			"fontFamily": 3,
			"textAlign": "left",
			"verticalAlign": "top",
			"baseline": 15,
			"containerId": null,
			"originalText": "6.확인 되었으니 access 토큰 줄게",
			"lineHeight": 1.2
		},
		{
			"id": "p7ChPJCyvxkPgZzjTxmm3",
			"type": "arrow",
			"x": 2103.5512226620535,
			"y": 3479.773573345913,
			"width": 695.9791666666665,
			"height": 0,
			"angle": 0,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"groupIds": [
				"WLksZQtdcYjFrMDoiwTCq"
			],
			"frameId": null,
			"roundness": null,
			"seed": 224335026,
			"version": 80,
			"versionNonce": 1616150962,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1724916934754,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					695.9791666666665,
					0
				]
			],
			"lastCommittedPoint": [
				695.9791666666665,
				0
			],
			"startBinding": null,
			"endBinding": null,
			"startArrowhead": null,
			"endArrowhead": "arrow"
		},
		{
			"id": "aQMQtR77",
			"type": "text",
			"x": 2131.603305995387,
			"y": 3441.7527400125796,
			"width": 349.5599670410156,
			"height": 19.2,
			"angle": 0,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"groupIds": [
				"WLksZQtdcYjFrMDoiwTCq"
			],
			"frameId": null,
			"roundness": null,
			"seed": 968713842,
			"version": 230,
			"versionNonce": 1584605806,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1724916934754,
			"link": null,
			"locked": false,
			"text": "7.Access 토큰 줄게, 유저의 resource 다오. ",
			"rawText": "7.Access 토큰 줄게, 유저의 resource 다오. ",
			"fontSize": 16,
			"fontFamily": 3,
			"textAlign": "left",
			"verticalAlign": "top",
			"baseline": 15,
			"containerId": null,
			"originalText": "7.Access 토큰 줄게, 유저의 resource 다오. ",
			"lineHeight": 1.2
		},
		{
			"id": "_niTJar5r_MoBXw3svriL",
			"type": "arrow",
			"x": 2801.12413932872,
			"y": 3523.1850316792465,
			"width": 364.5729166666665,
			"height": 0,
			"angle": 0,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"groupIds": [
				"WLksZQtdcYjFrMDoiwTCq"
			],
			"frameId": null,
			"roundness": null,
			"seed": 1627547570,
			"version": 79,
			"versionNonce": 1434286962,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1724916934754,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					-364.5729166666665,
					0
				]
			],
			"lastCommittedPoint": null,
			"startBinding": null,
			"endBinding": null,
			"startArrowhead": null,
			"endArrowhead": "arrow"
		},
		{
			"id": "C0HCjBOfQrtM4GJlbGaoy",
			"type": "arrow",
			"x": 2436.1033059953866,
			"y": 3563.7319066792465,
			"width": 362.2447916666665,
			"height": 0,
			"angle": 0,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"groupIds": [
				"WLksZQtdcYjFrMDoiwTCq"
			],
			"frameId": null,
			"roundness": null,
			"seed": 647212530,
			"version": 80,
			"versionNonce": 1740614830,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1724916934754,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					362.2447916666665,
					0
				]
			],
			"lastCommittedPoint": [
				362.2447916666665,
				0
			],
			"startBinding": null,
			"endBinding": null,
			"startArrowhead": null,
			"endArrowhead": "arrow"
		},
		{
			"id": "S6sft3-pHkCyasrGhzj5l",
			"type": "rectangle",
			"x": 2532.212680995386,
			"y": 3506.3829483459126,
			"width": 173,
			"height": 75,
			"angle": 0,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#e6fcf5",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"groupIds": [
				"WLksZQtdcYjFrMDoiwTCq"
			],
			"frameId": null,
			"roundness": null,
			"seed": 260444530,
			"version": 149,
			"versionNonce": 920730930,
			"isDeleted": false,
			"boundElements": [
				{
					"type": "text",
					"id": "m8N1kkim"
				}
			],
			"updated": 1724916934754,
			"link": null,
			"locked": false
		},
		{
			"id": "m8N1kkim",
			"type": "text",
			"x": 2579.4251901506595,
			"y": 3534.2829483459127,
			"width": 78.57498168945312,
			"height": 19.2,
			"angle": 0,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"groupIds": [
				"WLksZQtdcYjFrMDoiwTCq"
			],
			"frameId": null,
			"roundness": null,
			"seed": 1891365230,
			"version": 138,
			"versionNonce": 281143022,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1724916934754,
			"link": null,
			"locked": false,
			"text": "유효성 검증",
			"rawText": "유효성 검증",
			"fontSize": 16,
			"fontFamily": 3,
			"textAlign": "center",
			"verticalAlign": "middle",
			"baseline": 15,
			"containerId": "S6sft3-pHkCyasrGhzj5l",
			"originalText": "유효성 검증",
			"lineHeight": 1.2
		},
		{
			"type": "rectangle",
			"version": 687,
			"versionNonce": 1105643250,
			"isDeleted": false,
			"id": "XwR8bLADSoI4inqN3CKLs",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1853.0816502936323,
			"y": 3031.1532334336334,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#f3f0ff",
			"width": 150,
			"height": 30,
			"seed": 1607844270,
			"groupIds": [
				"WLksZQtdcYjFrMDoiwTCq"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"type": "text",
					"id": "NnjX4Png"
				}
			],
			"updated": 1724916934754,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 643,
			"versionNonce": 1241700654,
			"isDeleted": false,
			"id": "NnjX4Png",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1879.4105229742963,
			"y": 3036.590019147919,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 97.34225463867188,
			"height": 19.126428571428605,
			"seed": 659381230,
			"groupIds": [
				"WLksZQtdcYjFrMDoiwTCq"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1724916934754,
			"link": null,
			"locked": false,
			"fontSize": 15.938690476190505,
			"fontFamily": 3,
			"text": "유저의 ID/PW",
			"rawText": "유저의 ID/PW",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "XwR8bLADSoI4inqN3CKLs",
			"originalText": "유저의 ID/PW",
			"lineHeight": 1.2,
			"baseline": 15
		},
		{
			"type": "rectangle",
			"version": 883,
			"versionNonce": 1863653554,
			"isDeleted": false,
			"id": "iExVz-4HHZpH9dxFAQoZk",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2166.240536450217,
			"y": 3114.9395821178427,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#f8f1ee",
			"width": 219,
			"height": 30,
			"seed": 244167342,
			"groupIds": [
				"WLksZQtdcYjFrMDoiwTCq"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"type": "text",
					"id": "YytE6noV"
				}
			],
			"updated": 1724916934754,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 893,
			"versionNonce": 183206766,
			"isDeleted": false,
			"id": "YytE6noV",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2191.734677075217,
			"y": 3120.3763678321284,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 168.01171875,
			"height": 19.126428571428605,
			"seed": 2078223598,
			"groupIds": [
				"WLksZQtdcYjFrMDoiwTCq"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1724916934755,
			"link": null,
			"locked": false,
			"fontSize": 15.938690476190505,
			"fontFamily": 3,
			"text": "Authorization code",
			"rawText": "Authorization code",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "iExVz-4HHZpH9dxFAQoZk",
			"originalText": "Authorization code",
			"lineHeight": 1.2,
			"baseline": 15
		},
		{
			"type": "rectangle",
			"version": 942,
			"versionNonce": 236139122,
			"isDeleted": false,
			"id": "3RH1Fw7MZUsq4OOIQvDU4",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2133.4429441532816,
			"y": 3222.2839900125796,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#e7f5ff",
			"width": 219,
			"height": 30,
			"seed": 1695375214,
			"groupIds": [
				"WLksZQtdcYjFrMDoiwTCq"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"type": "text",
					"id": "2nChsSUv"
				}
			],
			"updated": 1724916934755,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 977,
			"versionNonce": 1975838126,
			"isDeleted": false,
			"id": "2nChsSUv",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2163.6040769657816,
			"y": 3227.720775726865,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 158.677734375,
			"height": 19.126428571428605,
			"seed": 1732985262,
			"groupIds": [
				"WLksZQtdcYjFrMDoiwTCq"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1724916934755,
			"link": null,
			"locked": false,
			"fontSize": 15.938690476190505,
			"fontFamily": 3,
			"text": "Client credential",
			"rawText": "Client credential",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "3RH1Fw7MZUsq4OOIQvDU4",
			"originalText": "Client credential",
			"lineHeight": 1.2,
			"baseline": 15
		},
		{
			"type": "rectangle",
			"version": 974,
			"versionNonce": 1638405170,
			"isDeleted": false,
			"id": "n5YM8C-tfA4RNf0O_LpEe",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2133.475838890123,
			"y": 3252.111292644158,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#f8f1ee",
			"width": 219,
			"height": 30,
			"seed": 1379944626,
			"groupIds": [
				"WLksZQtdcYjFrMDoiwTCq"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"type": "text",
					"id": "JJsz5ON1"
				}
			],
			"updated": 1724916934755,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 983,
			"versionNonce": 2075656174,
			"isDeleted": false,
			"id": "JJsz5ON1",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2158.969979515123,
			"y": 3257.5480783584435,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 168.01171875,
			"height": 19.126428571428605,
			"seed": 1146643058,
			"groupIds": [
				"WLksZQtdcYjFrMDoiwTCq"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1724916934755,
			"link": null,
			"locked": false,
			"fontSize": 15.938690476190505,
			"fontFamily": 3,
			"text": "Authorization code",
			"rawText": "Authorization code",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "n5YM8C-tfA4RNf0O_LpEe",
			"originalText": "Authorization code",
			"lineHeight": 1.2,
			"baseline": 15
		},
		{
			"type": "rectangle",
			"version": 1013,
			"versionNonce": 1002094066,
			"isDeleted": false,
			"id": "3iZ-twYpVVHpVnXL-NN_E",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2168.315477048019,
			"y": 3389.0685294862647,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#fff9db",
			"width": 219,
			"height": 30,
			"seed": 1879969518,
			"groupIds": [
				"WLksZQtdcYjFrMDoiwTCq"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"type": "text",
					"id": "ugHH2CuG"
				}
			],
			"updated": 1724916934755,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 1052,
			"versionNonce": 13488686,
			"isDeleted": false,
			"id": "ugHH2CuG",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2221.811570798019,
			"y": 3394.5053152005503,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 112.0078125,
			"height": 19.126428571428605,
			"seed": 1032454446,
			"groupIds": [
				"WLksZQtdcYjFrMDoiwTCq"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1724916934755,
			"link": null,
			"locked": false,
			"fontSize": 15.938690476190505,
			"fontFamily": 3,
			"text": "Access Token",
			"rawText": "Access Token",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "3iZ-twYpVVHpVnXL-NN_E",
			"originalText": "Access Token",
			"lineHeight": 1.2,
			"baseline": 15
		},
		{
			"type": "rectangle",
			"version": 1139,
			"versionNonce": 424816562,
			"isDeleted": false,
			"id": "MR93Wz2-O-phbxcxgxsBa",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2170.075345469071,
			"y": 3463.8958321178425,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#fff9db",
			"width": 219,
			"height": 30,
			"seed": 133887922,
			"groupIds": [
				"WLksZQtdcYjFrMDoiwTCq"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"type": "text",
					"id": "31vteV69"
				}
			],
			"updated": 1724916934755,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 1179,
			"versionNonce": 2146393198,
			"isDeleted": false,
			"id": "31vteV69",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2223.571439219071,
			"y": 3469.332617832128,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 112.0078125,
			"height": 19.126428571428605,
			"seed": 1826959730,
			"groupIds": [
				"WLksZQtdcYjFrMDoiwTCq"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1724916934755,
			"link": null,
			"locked": false,
			"fontSize": 15.938690476190505,
			"fontFamily": 3,
			"text": "Access Token",
			"rawText": "Access Token",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "MR93Wz2-O-phbxcxgxsBa",
			"originalText": "Access Token",
			"lineHeight": 1.2,
			"baseline": 15
		},
		{
			"id": "_zP-W7mBC4vwtmWmKo7Tx",
			"type": "arrow",
			"x": 2801.6436020480182,
			"y": 3657.8843189599474,
			"width": 693.050986842105,
			"height": 0,
			"angle": 0,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#fff9db",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"groupIds": [
				"WLksZQtdcYjFrMDoiwTCq"
			],
			"frameId": null,
			"roundness": null,
			"seed": 1667133678,
			"version": 73,
			"versionNonce": 1049979250,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1724916934755,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					-693.050986842105,
					0
				]
			],
			"lastCommittedPoint": [
				-693.050986842105,
				0
			],
			"startBinding": null,
			"endBinding": null,
			"startArrowhead": null,
			"endArrowhead": "arrow"
		},
		{
			"id": "Yeak6ts2",
			"type": "text",
			"x": 2502.6592270480182,
			"y": 3607.4279044862633,
			"width": 246.43496704101562,
			"height": 19.2,
			"angle": 0,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#fff9db",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"groupIds": [
				"WLksZQtdcYjFrMDoiwTCq"
			],
			"frameId": null,
			"roundness": null,
			"seed": 646792754,
			"version": 288,
			"versionNonce": 786800302,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1724916934755,
			"link": null,
			"locked": false,
			"text": "8.토큰이 유효하니 resource 줄게",
			"rawText": "8.토큰이 유효하니 resource 줄게",
			"fontSize": 16,
			"fontFamily": 3,
			"textAlign": "left",
			"verticalAlign": "top",
			"baseline": 15,
			"containerId": null,
			"originalText": "8.토큰이 유효하니 resource 줄게",
			"lineHeight": 1.2
		},
		{
			"type": "rectangle",
			"version": 1388,
			"versionNonce": 1389062962,
			"isDeleted": false,
			"id": "NFVlM4Q0sbiRJVy6fB1Rx",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2522.534227048019,
			"y": 3641.8275755388954,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#fff5f5",
			"width": 219,
			"height": 30,
			"seed": 1561976686,
			"groupIds": [
				"WLksZQtdcYjFrMDoiwTCq"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"type": "text",
					"id": "Yq42xC6U"
				}
			],
			"updated": 1724916934755,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 1440,
			"versionNonce": 576297198,
			"isDeleted": false,
			"id": "Yq42xC6U",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2594.698289548019,
			"y": 3647.264361253181,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "transparent",
			"width": 74.671875,
			"height": 19.126428571428605,
			"seed": 700957102,
			"groupIds": [
				"WLksZQtdcYjFrMDoiwTCq"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1724916934755,
			"link": null,
			"locked": false,
			"fontSize": 15.938690476190505,
			"fontFamily": 3,
			"text": "resource",
			"rawText": "resource",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "NFVlM4Q0sbiRJVy6fB1Rx",
			"originalText": "resource",
			"lineHeight": 1.2,
			"baseline": 15
		},
		{
			"type": "ellipse",
			"version": 93,
			"versionNonce": 2086352114,
			"isDeleted": false,
			"id": "CGuItKEPpYM3j6K1457_o",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1821.0728246632984,
			"y": 4127.038703058197,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#1e1e1e",
			"width": 33.35920827821246,
			"height": 33.35920827821246,
			"seed": 1211095538,
			"groupIds": [
				"G_JwGDzowygO_eKnWZVGB",
				"PBLIGC9bYHjxc67gc2by7"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1724916934755,
			"link": null,
			"locked": false
		},
		{
			"type": "ellipse",
			"version": 165,
			"versionNonce": 1909738286,
			"isDeleted": false,
			"id": "FrBPXJmIU0Xa_etZzaikr",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1810.7840677844247,
			"y": 4163.760714299531,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#1e1e1e",
			"width": 53.93672203596043,
			"height": 14.899296688041431,
			"seed": 281267122,
			"groupIds": [
				"G_JwGDzowygO_eKnWZVGB",
				"PBLIGC9bYHjxc67gc2by7"
			],
			"frameId": null,
			"roundness": {
				"type": 2
			},
			"boundElements": [],
			"updated": 1724916934755,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 80,
			"versionNonce": 2093729458,
			"isDeleted": false,
			"id": "2SRlG_y59S3PX4CxMc41V",
			"fillStyle": "solid",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 1810.469597522413,
			"y": 4171.820282788824,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#1e1e1e",
			"width": 54.56566255998325,
			"height": 19.55548540621112,
			"seed": 225674610,
			"groupIds": [
				"G_JwGDzowygO_eKnWZVGB",
				"PBLIGC9bYHjxc67gc2by7"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1724916934755,
			"link": null,
			"locked": false
		},
		{
			"id": "YTiq9YiE",
			"type": "text",
			"x": 1881.7576371357382,
			"y": 4118.202027293284,
			"width": 143.75497436523438,
			"height": 19.2,
			"angle": 0,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#fff5f5",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"groupIds": [
				"PBLIGC9bYHjxc67gc2by7"
			],
			"frameId": null,
			"roundness": null,
			"seed": 914647406,
			"version": 97,
			"versionNonce": 1539224942,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1724916934755,
			"link": null,
			"locked": false,
			"text": "1.새 계정 생성 요청",
			"rawText": "1.새 계정 생성 요청",
			"fontSize": 16,
			"fontFamily": 3,
			"textAlign": "left",
			"verticalAlign": "top",
			"baseline": 15,
			"containerId": null,
			"originalText": "1.새 계정 생성 요청",
			"lineHeight": 1.2
		},
		{
			"id": "AClnVryvuc51TU2f3hfyG",
			"type": "diamond",
			"x": 2060.731595469072,
			"y": 4095.833769361141,
			"width": 271,
			"height": 134,
			"angle": 0,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#2f9e44",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"groupIds": [
				"PBLIGC9bYHjxc67gc2by7"
			],
			"frameId": null,
			"roundness": null,
			"seed": 1336737202,
			"version": 599,
			"versionNonce": 1287921778,
			"isDeleted": false,
			"boundElements": [
				{
					"type": "text",
					"id": "s1TMRscW"
				},
				{
					"id": "XyroLibT7VtSb8pxTY2E8",
					"type": "arrow"
				},
				{
					"id": "jotA6fHa_s-KODClqk4iT",
					"type": "arrow"
				},
				{
					"id": "NOv6_zF8cz5rbRdu3efj9",
					"type": "arrow"
				}
			],
			"updated": 1724916934755,
			"link": null,
			"locked": false
		},
		{
			"id": "s1TMRscW",
			"type": "text",
			"x": 2140.231595469072,
			"y": 4143.633769361141,
			"width": 112.5,
			"height": 38.4,
			"angle": 0,
			"strokeColor": "#ffffff",
			"backgroundColor": "#fff5f5",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"groupIds": [
				"PBLIGC9bYHjxc67gc2by7"
			],
			"frameId": null,
			"roundness": null,
			"seed": 302233842,
			"version": 13,
			"versionNonce": 1768019886,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1724916934755,
			"link": null,
			"locked": false,
			"text": "Account \nMicroservice",
			"rawText": "Account Microservice",
			"fontSize": 16,
			"fontFamily": 3,
			"textAlign": "center",
			"verticalAlign": "middle",
			"baseline": 34,
			"containerId": "AClnVryvuc51TU2f3hfyG",
			"originalText": "Account Microservice",
			"lineHeight": 1.2
		},
		{
			"id": "wOiPKwkA",
			"type": "text",
			"x": 2071.846178802404,
			"y": 4243.097860626618,
			"width": 229.01998901367188,
			"height": 57.599999999999994,
			"angle": 0,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#fff5f5",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"groupIds": [
				"PBLIGC9bYHjxc67gc2by7"
			],
			"frameId": null,
			"roundness": null,
			"seed": 2054097266,
			"version": 502,
			"versionNonce": 940261938,
			"isDeleted": false,
			"boundElements": [],
			"updated": 1724916934755,
			"link": null,
			"locked": false,
			"text": "2.새 계정을 생성한다.\n  event broker에 push한다.\n  end user에게 응답한다.",
			"rawText": "2.새 계정을 생성한다.\n  event broker에 push한다.\n  end user에게 응답한다.",
			"fontSize": 16,
			"fontFamily": 3,
			"textAlign": "left",
			"verticalAlign": "top",
			"baseline": 53,
			"containerId": null,
			"originalText": "2.새 계정을 생성한다.\n  event broker에 push한다.\n  end user에게 응답한다.",
			"lineHeight": 1.2
		},
		{
			"id": "XyroLibT7VtSb8pxTY2E8",
			"type": "arrow",
			"x": 1890.2055538024042,
			"y": 4153.80619395995,
			"width": 160.75532975627675,
			"height": 0,
			"angle": 0,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#fff5f5",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"groupIds": [
				"PBLIGC9bYHjxc67gc2by7"
			],
			"frameId": null,
			"roundness": null,
			"seed": 1988636846,
			"version": 176,
			"versionNonce": 1761099186,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1724917055812,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					160.75532975627675,
					0
				]
			],
			"lastCommittedPoint": [
				148.93229166666652,
				0
			],
			"startBinding": null,
			"endBinding": {
				"elementId": "AClnVryvuc51TU2f3hfyG",
				"gap": 13.302778990122562,
				"focus": 0.13473993136105844
			},
			"startArrowhead": null,
			"endArrowhead": "arrow"
		},
		{
			"id": "jotA6fHa_s-KODClqk4iT",
			"type": "arrow",
			"x": 2048.5460644125487,
			"y": 4176.49369395995,
			"width": 161.76238561014452,
			"height": 0,
			"angle": 0,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#fff5f5",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"groupIds": [
				"PBLIGC9bYHjxc67gc2by7"
			],
			"frameId": null,
			"roundness": null,
			"seed": 472826990,
			"version": 177,
			"versionNonce": 1878601326,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1724917055812,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					-161.76238561014452,
					0
				]
			],
			"lastCommittedPoint": [
				-154.14583333333303,
				0
			],
			"startBinding": {
				"elementId": "AClnVryvuc51TU2f3hfyG",
				"gap": 18.305209836946588,
				"focus": -0.20387947162401615
			},
			"endBinding": null,
			"startArrowhead": null,
			"endArrowhead": "arrow"
		},
		{
			"id": "Qfcx7JwD",
			"type": "text",
			"x": 1874.7003454690707,
			"y": 4206.660360626616,
			"width": 180.80996704101562,
			"height": 19.2,
			"angle": 0,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#fff5f5",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"groupIds": [
				"PBLIGC9bYHjxc67gc2by7"
			],
			"frameId": null,
			"roundness": null,
			"seed": 494569070,
			"version": 113,
			"versionNonce": 1666597934,
			"isDeleted": false,
			"boundElements": [],
			"updated": 1724916934755,
			"link": null,
			"locked": false,
			"text": "3.새 계정 생성 완료 응답",
			"rawText": "3.새 계정 생성 완료 응답",
			"fontSize": 16,
			"fontFamily": 3,
			"textAlign": "left",
			"verticalAlign": "top",
			"baseline": 15,
			"containerId": null,
			"originalText": "3.새 계정 생성 완료 응답",
			"lineHeight": 1.2
		},
		{
			"id": "NOv6_zF8cz5rbRdu3efj9",
			"type": "arrow",
			"x": 2335.1359875168523,
			"y": 4164.504110626616,
			"width": 159.26748295221842,
			"height": 0,
			"angle": 0,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#fff5f5",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"groupIds": [
				"PBLIGC9bYHjxc67gc2by7"
			],
			"frameId": null,
			"roundness": null,
			"seed": 227537582,
			"version": 200,
			"versionNonce": 172603250,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1724917055812,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					159.26748295221842,
					0
				]
			],
			"lastCommittedPoint": [
				145.63020833333348,
				0
			],
			"startBinding": {
				"elementId": "AClnVryvuc51TU2f3hfyG",
				"gap": 3.792087177022367,
				"focus": 0.024930466648882755
			},
			"endBinding": null,
			"startArrowhead": null,
			"endArrowhead": "arrow"
		},
		{
			"type": "rectangle",
			"version": 101,
			"versionNonce": 479825518,
			"isDeleted": false,
			"id": "L9dx5IDM2yHF7N5B977s-",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2535.1065954690707,
			"y": 4138.842652293284,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"width": 191,
			"height": 57,
			"seed": 837424622,
			"groupIds": [
				"PBLIGC9bYHjxc67gc2by7"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"type": "text",
					"id": "CD2AwPFB"
				}
			],
			"updated": 1724916934755,
			"link": null,
			"locked": false
		},
		{
			"id": "CD2AwPFB",
			"type": "text",
			"x": 2574.3565954690707,
			"y": 4157.742652293284,
			"width": 112.5,
			"height": 19.2,
			"angle": 0,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#2f9e44",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "dashed",
			"roughness": 0,
			"opacity": 100,
			"groupIds": [
				"PBLIGC9bYHjxc67gc2by7"
			],
			"frameId": null,
			"roundness": null,
			"seed": 1757116978,
			"version": 37,
			"versionNonce": 1046435698,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1724916934755,
			"link": null,
			"locked": false,
			"text": "Event broker",
			"rawText": "Event broker",
			"fontSize": 16,
			"fontFamily": 3,
			"textAlign": "center",
			"verticalAlign": "middle",
			"baseline": 15,
			"containerId": "L9dx5IDM2yHF7N5B977s-",
			"originalText": "Event broker",
			"lineHeight": 1.2
		},
		{
			"id": "ZFdnyKLB",
			"type": "text",
			"x": 2442.471178802404,
			"y": 4211.63431895995,
			"width": 427.24493408203125,
			"height": 38.4,
			"angle": 0,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#2f9e44",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "dashed",
			"roughness": 0,
			"opacity": 100,
			"groupIds": [
				"PBLIGC9bYHjxc67gc2by7"
			],
			"frameId": null,
			"roundness": null,
			"seed": 2085695022,
			"version": 463,
			"versionNonce": 1534693550,
			"isDeleted": false,
			"boundElements": [],
			"updated": 1724916934755,
			"link": null,
			"locked": false,
			"text": "3.event broker가 이벤트의 세부 사항을 큐에 저장한다.\n  큐를 구독하고 있는 subscriber가 이벤트를 읽도록 한다.",
			"rawText": "3.event broker가 이벤트의 세부 사항을 큐에 저장한다.\n  큐를 구독하고 있는 subscriber가 이벤트를 읽도록 한다.",
			"fontSize": 16,
			"fontFamily": 3,
			"textAlign": "left",
			"verticalAlign": "top",
			"baseline": 34,
			"containerId": null,
			"originalText": "3.event broker가 이벤트의 세부 사항을 큐에 저장한다.\n  큐를 구독하고 있는 subscriber가 이벤트를 읽도록 한다.",
			"lineHeight": 1.2
		},
		{
			"type": "diamond",
			"version": 790,
			"versionNonce": 1596430642,
			"isDeleted": false,
			"id": "WMGbP2e-wduiMPO1LZBDc",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2937.721178802404,
			"y": 4094.3009856266153,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#1971c2",
			"width": 271,
			"height": 134,
			"seed": 1667878002,
			"groupIds": [
				"PBLIGC9bYHjxc67gc2by7"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"type": "text",
					"id": "md2SOyCH"
				},
				{
					"id": "Hb7jDbKRMdlBa9p669kTJ",
					"type": "arrow"
				}
			],
			"updated": 1724916934755,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 226,
			"versionNonce": 1000295150,
			"isDeleted": false,
			"id": "md2SOyCH",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 3040.658678802404,
			"y": 4142.1009856266155,
			"strokeColor": "#ffffff",
			"backgroundColor": "#fff5f5",
			"width": 65.625,
			"height": 38.4,
			"seed": 1159425586,
			"groupIds": [
				"PBLIGC9bYHjxc67gc2by7"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1724916934755,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 3,
			"text": "Message\nservice",
			"rawText": "Message\nservice",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "WMGbP2e-wduiMPO1LZBDc",
			"originalText": "Message\nservice",
			"lineHeight": 1.2,
			"baseline": 34
		},
		{
			"id": "5SNrjoB5",
			"type": "text",
			"x": 2921.7211788024047,
			"y": 4252.103068959951,
			"width": 454.034912109375,
			"height": 38.4,
			"angle": 0,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#1971c2",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"groupIds": [
				"PBLIGC9bYHjxc67gc2by7"
			],
			"frameId": null,
			"roundness": null,
			"seed": 556907758,
			"version": 244,
			"versionNonce": 1224844018,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1724916934756,
			"link": null,
			"locked": false,
			"text": "4.event broker로부터 알림을 받고 큐의 내용을 읽는다.\n  이메일 또는 SMS를 통해 사용자에게 메시지를 전송하도록 한다.",
			"rawText": "4.event broker로부터 알림을 받고 큐의 내용을 읽는다.\n  이메일 또는 SMS를 통해 사용자에게 메시지를 전송하도록 한다.",
			"fontSize": 16,
			"fontFamily": 3,
			"textAlign": "left",
			"verticalAlign": "top",
			"baseline": 34,
			"containerId": null,
			"originalText": "4.event broker로부터 알림을 받고 큐의 내용을 읽는다.\n  이메일 또는 SMS를 통해 사용자에게 메시지를 전송하도록 한다.",
			"lineHeight": 1.2
		},
		{
			"id": "OIlqRIxH",
			"type": "text",
			"x": 2783.9607621357386,
			"y": 4065.1030689599506,
			"width": 617.8748779296875,
			"height": 19.2,
			"angle": 0,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#1971c2",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"groupIds": [
				"PBLIGC9bYHjxc67gc2by7"
			],
			"frameId": null,
			"roundness": null,
			"seed": 1149476334,
			"version": 234,
			"versionNonce": 2073279790,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1724916934756,
			"link": null,
			"locked": false,
			"text": "Message service: 이벤트 브로커 내부에서 queue를 지속적으로 모니터링 하는 서비스",
			"rawText": "Message service: 이벤트 브로커 내부에서 queue를 지속적으로 모니터링 하는 서비스",
			"fontSize": 16,
			"fontFamily": 3,
			"textAlign": "left",
			"verticalAlign": "top",
			"baseline": 15,
			"containerId": null,
			"originalText": "Message service: 이벤트 브로커 내부에서 queue를 지속적으로 모니터링 하는 서비스",
			"lineHeight": 1.2
		},
		{
			"id": "Hb7jDbKRMdlBa9p669kTJ",
			"type": "arrow",
			"x": 2931.6933973343494,
			"y": 4164.573121043286,
			"width": 185.08159353194424,
			"height": 0,
			"angle": 0,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#1971c2",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"groupIds": [
				"PBLIGC9bYHjxc67gc2by7"
			],
			"frameId": null,
			"roundness": null,
			"seed": 2021771694,
			"version": 227,
			"versionNonce": 1642410158,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1724917055816,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					-185.08159353194424,
					0
				]
			],
			"lastCommittedPoint": [
				-176.42578125,
				0
			],
			"startBinding": {
				"elementId": "WMGbP2e-wduiMPO1LZBDc",
				"gap": 6.858645610589278,
				"focus": -0.04883784203985981
			},
			"endBinding": null,
			"startArrowhead": null,
			"endArrowhead": "arrow"
		},
		{
			"id": "JJ2PgKAtbaJ3V4oisMWFK",
			"type": "rectangle",
			"x": 1776.4068439788077,
			"y": 4049.3734456351463,
			"width": 421.8750000000002,
			"height": 278.60390881894364,
			"angle": 0,
			"strokeColor": "transparent",
			"backgroundColor": "#d0bfff33",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"groupIds": [
				"PBLIGC9bYHjxc67gc2by7"
			],
			"frameId": null,
			"roundness": null,
			"seed": 1180523122,
			"version": 132,
			"versionNonce": 549447534,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1724916934756,
			"link": null,
			"locked": false
		},
		{
			"type": "rectangle",
			"version": 391,
			"versionNonce": 958860914,
			"isDeleted": false,
			"id": "bYK2K0Jx2i4wfJDwlQDra",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2196.5901370956335,
			"y": 4049.1793365934423,
			"strokeColor": "transparent",
			"backgroundColor": "#ffec9933",
			"width": 1206.9537777610967,
			"height": 278.4252763496884,
			"seed": 116809458,
			"groupIds": [
				"PBLIGC9bYHjxc67gc2by7"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1724916934756,
			"link": null,
			"locked": false
		},
		{
			"id": "agTpK3Fk",
			"type": "text",
			"x": 2106.7422350883517,
			"y": 4050.938846414947,
			"width": 194.34375,
			"height": 33.17104327078156,
			"angle": 0,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec9933",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"groupIds": [
				"PBLIGC9bYHjxc67gc2by7"
			],
			"frameId": null,
			"roundness": null,
			"seed": 1854169262,
			"version": 178,
			"versionNonce": 460114350,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1724916934756,
			"link": null,
			"locked": false,
			"text": "Sync | Async",
			"rawText": "Sync | Async",
			"fontSize": 27.642536058984636,
			"fontFamily": 3,
			"textAlign": "left",
			"verticalAlign": "top",
			"baseline": 27,
			"containerId": null,
			"originalText": "Sync | Async",
			"lineHeight": 1.2
		},
		{
			"type": "text",
			"version": 634,
			"versionNonce": 903901234,
			"isDeleted": false,
			"id": "6C8sH1YN",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2920.1015925716843,
			"y": 4337.466709213623,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#1971c2",
			"width": 597.3449096679688,
			"height": 19.2,
			"seed": 1203817198,
			"groupIds": [
				"PBLIGC9bYHjxc67gc2by7"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1724916934756,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 3,
			"text": "5.메시지가 사용자에게 전송되면 전송이 완료되었다는 메시지를 이벤트 큐에 push한다.",
			"rawText": "5.메시지가 사용자에게 전송되면 전송이 완료되었다는 메시지를 이벤트 큐에 push한다.",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "5.메시지가 사용자에게 전송되면 전송이 완료되었다는 메시지를 이벤트 큐에 push한다.",
			"lineHeight": 1.2,
			"baseline": 15
		},
		{
			"type": "text",
			"version": 692,
			"versionNonce": 1791189998,
			"isDeleted": false,
			"id": "IKqbQXYW",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "dashed",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2441.937483157736,
			"y": 4336.736497637377,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#2f9e44",
			"width": 427.24493408203125,
			"height": 38.4,
			"seed": 1903751730,
			"groupIds": [
				"PBLIGC9bYHjxc67gc2by7"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1724916934756,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 3,
			"text": "6.event broker가 이벤트의 세부 사항을 큐에 저장한다.\n  큐를 구독하고 있는 subscriber가 이벤트를 읽도록 한다.",
			"rawText": "6.event broker가 이벤트의 세부 사항을 큐에 저장한다.\n  큐를 구독하고 있는 subscriber가 이벤트를 읽도록 한다.",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "6.event broker가 이벤트의 세부 사항을 큐에 저장한다.\n  큐를 구독하고 있는 subscriber가 이벤트를 읽도록 한다.",
			"lineHeight": 1.2,
			"baseline": 34
		},
		{
			"type": "text",
			"version": 1029,
			"versionNonce": 545757682,
			"isDeleted": false,
			"id": "967EcfBy",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "dashed",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2019.535503476773,
			"y": 4340.9548191658505,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#2f9e44",
			"width": 393.3199157714844,
			"height": 38.4,
			"seed": 1398453806,
			"groupIds": [
				"PBLIGC9bYHjxc67gc2by7"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1724916934756,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 3,
			"text": "7.이벤트 브로커의 큐에서 완료되었다는 이벤트를 읽는다.\n  전송 되었다는 데이터를 DB에 업데이트한다.",
			"rawText": "7.이벤트 브로커의 큐에서 완료되었다는 이벤트를 읽는다.\n  전송 되었다는 데이터를 DB에 업데이트한다.",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "7.이벤트 브로커의 큐에서 완료되었다는 이벤트를 읽는다.\n  전송 되었다는 데이터를 DB에 업데이트한다.",
			"lineHeight": 1.2,
			"baseline": 34
		},
		{
			"id": "LVNMZplRNafk-4i82ehao",
			"type": "arrow",
			"x": 3054.0019348219184,
			"y": 4404.796393116005,
			"width": 866.7535307668277,
			"height": 0,
			"angle": 0,
			"strokeColor": "#868e96",
			"backgroundColor": "#ffec9933",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"groupIds": [
				"PBLIGC9bYHjxc67gc2by7"
			],
			"frameId": null,
			"roundness": null,
			"seed": 180063726,
			"version": 195,
			"versionNonce": 1087157806,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1724916934756,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					-866.7535307668277,
					0
				]
			],
			"lastCommittedPoint": [
				-1150.3345804649935,
				0
			],
			"startBinding": null,
			"endBinding": null,
			"startArrowhead": null,
			"endArrowhead": "arrow"
		},
		{
			"id": "KFCBOmQE",
			"type": "text",
			"x": 2504.4588170598454,
			"y": 4413.788054441644,
			"width": 234.375,
			"height": 19.2,
			"angle": 0,
			"strokeColor": "#868e96",
			"backgroundColor": "#ffec9933",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"groupIds": [
				"PBLIGC9bYHjxc67gc2by7"
			],
			"frameId": null,
			"roundness": null,
			"seed": 2030858542,
			"version": 123,
			"versionNonce": 136547250,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1724916934756,
			"link": null,
			"locked": false,
			"text": "reverse asynchronous flow",
			"rawText": "reverse asynchronous flow",
			"fontSize": 16,
			"fontFamily": 3,
			"textAlign": "left",
			"verticalAlign": "top",
			"baseline": 15,
			"containerId": null,
			"originalText": "reverse asynchronous flow",
			"lineHeight": 1.2
		},
		{
			"id": "vFqN7bM6K4nXJKfQAj58x",
			"type": "ellipse",
			"x": 1874.465534912957,
			"y": 4662.125846955866,
			"width": 123,
			"height": 123,
			"angle": 0,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffc9c9",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"groupIds": [
				"2wrwCb__lhHQ8CJtqbuf6"
			],
			"frameId": null,
			"roundness": null,
			"seed": 1164424370,
			"version": 183,
			"versionNonce": 439374258,
			"isDeleted": false,
			"boundElements": [
				{
					"type": "text",
					"id": "caPo81WL"
				},
				{
					"id": "SN7hgzr4Fs1YRMbwp02OE",
					"type": "arrow"
				}
			],
			"updated": 1724917058924,
			"link": null,
			"locked": false
		},
		{
			"id": "caPo81WL",
			"type": "text",
			"x": 1903.1659678699843,
			"y": 4715.238779912894,
			"width": 65.625,
			"height": 16.79999999999999,
			"angle": 0,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec9933",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"groupIds": [
				"2wrwCb__lhHQ8CJtqbuf6"
			],
			"frameId": null,
			"roundness": null,
			"seed": 278148270,
			"version": 399,
			"versionNonce": 486300270,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1724917058924,
			"link": null,
			"locked": false,
			"text": "Producer",
			"rawText": "Producer",
			"fontSize": 13.999999999999993,
			"fontFamily": 3,
			"textAlign": "center",
			"verticalAlign": "middle",
			"baseline": 13,
			"containerId": "vFqN7bM6K4nXJKfQAj58x",
			"originalText": "Producer",
			"lineHeight": 1.2
		},
		{
			"id": "kHS6xWMAPupzyPkKRFsh5",
			"type": "rectangle",
			"x": 2079.7972402090045,
			"y": 4568.907581596572,
			"width": 378.19829769454185,
			"height": 314.6155301281815,
			"angle": 0,
			"strokeColor": "#2f9e44",
			"backgroundColor": "#b2f2bb",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"groupIds": [
				"2wrwCb__lhHQ8CJtqbuf6"
			],
			"frameId": null,
			"roundness": null,
			"seed": 269332974,
			"version": 132,
			"versionNonce": 56576882,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1724917058924,
			"link": null,
			"locked": false
		},
		{
			"id": "0NoJPmx7RoM1yKACV8xbf",
			"type": "rectangle",
			"x": 2114.885959890572,
			"y": 4679.215346660662,
			"width": 95,
			"height": 94,
			"angle": 0,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#a5d8ff",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"groupIds": [
				"2wrwCb__lhHQ8CJtqbuf6"
			],
			"frameId": null,
			"roundness": null,
			"seed": 1111354226,
			"version": 124,
			"versionNonce": 1570954414,
			"isDeleted": false,
			"boundElements": [
				{
					"type": "text",
					"id": "D7HafStZ"
				},
				{
					"id": "SN7hgzr4Fs1YRMbwp02OE",
					"type": "arrow"
				},
				{
					"id": "PS5Ha9KckPIf-KdI_5bYj",
					"type": "arrow"
				},
				{
					"id": "L5dWoBrntQO3T73jNk9UC",
					"type": "arrow"
				}
			],
			"updated": 1724917058924,
			"link": null,
			"locked": false
		},
		{
			"id": "D7HafStZ",
			"type": "text",
			"x": 2124.885959890572,
			"y": 4716.615346660662,
			"width": 75,
			"height": 19.2,
			"angle": 0,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#a5d8ff",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"groupIds": [
				"2wrwCb__lhHQ8CJtqbuf6"
			],
			"frameId": null,
			"roundness": null,
			"seed": 2031465010,
			"version": 132,
			"versionNonce": 1745423666,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1724917058924,
			"link": null,
			"locked": false,
			"text": "Exchange",
			"rawText": "Exchange",
			"fontSize": 16,
			"fontFamily": 3,
			"textAlign": "center",
			"verticalAlign": "middle",
			"baseline": 15,
			"containerId": "0NoJPmx7RoM1yKACV8xbf",
			"originalText": "Exchange",
			"lineHeight": 1.2
		},
		{
			"id": "AmVA5_tKy907fjgSxwMTr",
			"type": "rectangle",
			"x": 2289.8475833578973,
			"y": 4653.024268022618,
			"width": 129,
			"height": 45,
			"angle": 0,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#a5d8ff",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"groupIds": [
				"2wrwCb__lhHQ8CJtqbuf6"
			],
			"frameId": null,
			"roundness": null,
			"seed": 1613548402,
			"version": 162,
			"versionNonce": 1119819502,
			"isDeleted": false,
			"boundElements": [
				{
					"type": "text",
					"id": "Prnc0hgg"
				},
				{
					"id": "PS5Ha9KckPIf-KdI_5bYj",
					"type": "arrow"
				},
				{
					"id": "oK-0mG4SBdKgqFdP9oANz",
					"type": "arrow"
				}
			],
			"updated": 1724917058924,
			"link": null,
			"locked": false
		},
		{
			"id": "Prnc0hgg",
			"type": "text",
			"x": 2326.2225833578973,
			"y": 4665.924268022618,
			"width": 56.25,
			"height": 19.2,
			"angle": 0,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#b2f2bb",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"groupIds": [
				"2wrwCb__lhHQ8CJtqbuf6"
			],
			"frameId": null,
			"roundness": null,
			"seed": 347887602,
			"version": 108,
			"versionNonce": 496277234,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1724917058924,
			"link": null,
			"locked": false,
			"text": "Queue1",
			"rawText": "Queue1",
			"fontSize": 16,
			"fontFamily": 3,
			"textAlign": "center",
			"verticalAlign": "middle",
			"baseline": 15,
			"containerId": "AmVA5_tKy907fjgSxwMTr",
			"originalText": "Queue1",
			"lineHeight": 1.2
		},
		{
			"type": "rectangle",
			"version": 228,
			"versionNonce": 618268974,
			"isDeleted": false,
			"id": "qHeYQQZ7i6NX1bjJqjsxe",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2289.8475833578973,
			"y": 4754.4064252987055,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#a5d8ff",
			"width": 129,
			"height": 45,
			"seed": 1201356530,
			"groupIds": [
				"2wrwCb__lhHQ8CJtqbuf6"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"type": "text",
					"id": "e0Q5TXkt"
				},
				{
					"id": "L5dWoBrntQO3T73jNk9UC",
					"type": "arrow"
				},
				{
					"id": "5rhoEy1jd5IYwCMkswHkh",
					"type": "arrow"
				}
			],
			"updated": 1724917058924,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 174,
			"versionNonce": 881387698,
			"isDeleted": false,
			"id": "e0Q5TXkt",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2326.2225833578973,
			"y": 4767.306425298705,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#b2f2bb",
			"width": 56.25,
			"height": 19.2,
			"seed": 930779314,
			"groupIds": [
				"2wrwCb__lhHQ8CJtqbuf6"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1724917058924,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 3,
			"text": "Queue1",
			"rawText": "Queue1",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "qHeYQQZ7i6NX1bjJqjsxe",
			"originalText": "Queue1",
			"lineHeight": 1.2,
			"baseline": 15
		},
		{
			"type": "ellipse",
			"version": 353,
			"versionNonce": 1667019630,
			"isDeleted": false,
			"id": "wqUrk3UBKKAAvcnhlq3Xm",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2552.4537964286205,
			"y": 4630.94045226087,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec9933",
			"width": 89,
			"height": 89,
			"seed": 1565342446,
			"groupIds": [
				"2wrwCb__lhHQ8CJtqbuf6"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"type": "text",
					"id": "V2J6w4XM"
				},
				{
					"id": "oK-0mG4SBdKgqFdP9oANz",
					"type": "arrow"
				}
			],
			"updated": 1724917058924,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 787,
			"versionNonce": 344785522,
			"isDeleted": false,
			"id": "V2J6w4XM",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2571.7541462283193,
			"y": 4669.726832077016,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec9933",
			"width": 50.466796875,
			"height": 11.494736842105256,
			"seed": 302230830,
			"groupIds": [
				"2wrwCb__lhHQ8CJtqbuf6"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1724917058924,
			"link": null,
			"locked": false,
			"fontSize": 9.578947368421048,
			"fontFamily": 3,
			"text": "Consumer1",
			"rawText": "Consumer1",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "wqUrk3UBKKAAvcnhlq3Xm",
			"originalText": "Consumer1",
			"lineHeight": 1.2,
			"baseline": 9
		},
		{
			"type": "ellipse",
			"version": 413,
			"versionNonce": 143660462,
			"isDeleted": false,
			"id": "oPxb9hrMOUNO9wrfeLxEE",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2552.949323523167,
			"y": 4734.935405334232,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec9933",
			"width": 89,
			"height": 89,
			"seed": 974850542,
			"groupIds": [
				"2wrwCb__lhHQ8CJtqbuf6"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [
				{
					"type": "text",
					"id": "OQgM2iWU"
				},
				{
					"id": "5rhoEy1jd5IYwCMkswHkh",
					"type": "arrow"
				}
			],
			"updated": 1724917058924,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 854,
			"versionNonce": 409461810,
			"isDeleted": false,
			"id": "OQgM2iWU",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2572.249673322866,
			"y": 4773.721785150378,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#ffec9933",
			"width": 50.466796875,
			"height": 11.494736842105256,
			"seed": 1379900462,
			"groupIds": [
				"2wrwCb__lhHQ8CJtqbuf6"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1724917058924,
			"link": null,
			"locked": false,
			"fontSize": 9.578947368421048,
			"fontFamily": 3,
			"text": "Consumer2",
			"rawText": "Consumer2",
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "oPxb9hrMOUNO9wrfeLxEE",
			"originalText": "Consumer2",
			"lineHeight": 1.2,
			"baseline": 9
		},
		{
			"id": "SN7hgzr4Fs1YRMbwp02OE",
			"type": "arrow",
			"x": 2003.218603858237,
			"y": 4726.402418103411,
			"width": 107.30886776675766,
			"height": 0,
			"angle": 0,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#b2f2bb",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"groupIds": [
				"2wrwCb__lhHQ8CJtqbuf6"
			],
			"frameId": null,
			"roundness": null,
			"seed": 757947954,
			"version": 4506,
			"versionNonce": 1461728750,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1725547071568,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					107.30886776675766,
					0
				]
			],
			"lastCommittedPoint": [
				107.30886776675766,
				0
			],
			"startBinding": {
				"elementId": "vFqN7bM6K4nXJKfQAj58x",
				"focus": 0.04514749833406387,
				"gap": 5.810360494473294
			},
			"endBinding": {
				"elementId": "0NoJPmx7RoM1yKACV8xbf",
				"focus": -0.003980243462737758,
				"gap": 4.358488265577307
			},
			"startArrowhead": null,
			"endArrowhead": "arrow"
		},
		{
			"id": "PS5Ha9KckPIf-KdI_5bYj",
			"type": "arrow",
			"x": 2220.6023087060603,
			"y": 4721.058491248474,
			"width": 62.95745134135086,
			"height": 42.525339596542835,
			"angle": 0,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#b2f2bb",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"groupIds": [
				"2wrwCb__lhHQ8CJtqbuf6"
			],
			"frameId": null,
			"roundness": null,
			"seed": 318772270,
			"version": 4520,
			"versionNonce": 1841252398,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1725547071568,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					62.95745134135086,
					-42.525339596542835
				]
			],
			"lastCommittedPoint": [
				64.45360672634433,
				-39.302851075019134
			],
			"startBinding": {
				"elementId": "0NoJPmx7RoM1yKACV8xbf",
				"focus": 0.4320199779330077,
				"gap": 10.716348815488345
			},
			"endBinding": {
				"elementId": "AmVA5_tKy907fjgSxwMTr",
				"focus": 0.6781810429116392,
				"gap": 6.2878233104861465
			},
			"startArrowhead": null,
			"endArrowhead": "arrow"
		},
		{
			"id": "L5dWoBrntQO3T73jNk9UC",
			"type": "arrow",
			"x": 2220.9943966733026,
			"y": 4721.749271989889,
			"width": 54.278964318760245,
			"height": 49.833235721054734,
			"angle": 0,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#b2f2bb",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"groupIds": [
				"2wrwCb__lhHQ8CJtqbuf6"
			],
			"frameId": null,
			"roundness": null,
			"seed": 517504878,
			"version": 4500,
			"versionNonce": 2067927662,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1725547071568,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					54.278964318760245,
					49.833235721054734
				]
			],
			"lastCommittedPoint": [
				56.63907206164777,
				51.015062332416164
			],
			"startBinding": {
				"elementId": "0NoJPmx7RoM1yKACV8xbf",
				"focus": -0.6431353689967104,
				"gap": 11.108436782730678
			},
			"endBinding": {
				"elementId": "qHeYQQZ7i6NX1bjJqjsxe",
				"focus": -0.8232512308729428,
				"gap": 14.57422236583443
			},
			"startArrowhead": null,
			"endArrowhead": "arrow"
		},
		{
			"id": "u1TjHEe0",
			"type": "text",
			"x": 2002.3671850471949,
			"y": 4690.5520262877635,
			"width": 102.67999267578125,
			"height": 19.2,
			"angle": 0,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#b2f2bb",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"groupIds": [
				"2wrwCb__lhHQ8CJtqbuf6"
			],
			"frameId": null,
			"roundness": null,
			"seed": 88152050,
			"version": 100,
			"versionNonce": 1583218610,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1724917058924,
			"link": null,
			"locked": false,
			"text": "message 전송",
			"rawText": "message 전송",
			"fontSize": 16,
			"fontFamily": 3,
			"textAlign": "left",
			"verticalAlign": "top",
			"baseline": 15,
			"containerId": null,
			"originalText": "message 전송",
			"lineHeight": 1.2
		},
		{
			"type": "text",
			"version": 182,
			"versionNonce": 1044941934,
			"isDeleted": false,
			"id": "RtrGqEOw",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2447.0186270904014,
			"y": 4639.632160176454,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#b2f2bb",
			"width": 102.67999267578125,
			"height": 19.2,
			"seed": 826244334,
			"groupIds": [
				"2wrwCb__lhHQ8CJtqbuf6"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1724917058924,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 3,
			"text": "message 수신",
			"rawText": "message 수신",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "message 수신",
			"lineHeight": 1.2,
			"baseline": 15
		},
		{
			"id": "oK-0mG4SBdKgqFdP9oANz",
			"type": "arrow",
			"x": 2549.2581302341036,
			"y": 4674.888772506858,
			"width": 129.41054687620635,
			"height": 0,
			"angle": 0,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#b2f2bb",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"groupIds": [
				"2wrwCb__lhHQ8CJtqbuf6"
			],
			"frameId": null,
			"roundness": null,
			"seed": 1588463794,
			"version": 4450,
			"versionNonce": 1517393070,
			"isDeleted": false,
			"boundElements": null,
			"updated": 1725547071569,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					-129.41054687620635,
					0
				]
			],
			"lastCommittedPoint": [
				-130.05035655949587,
				0
			],
			"startBinding": {
				"elementId": "wqUrk3UBKKAAvcnhlq3Xm",
				"focus": 0.012397297842970431,
				"gap": 3.1988566350365204
			},
			"endBinding": {
				"elementId": "AmVA5_tKy907fjgSxwMTr",
				"focus": -0.028244245144903996,
				"gap": 1
			},
			"startArrowhead": null,
			"endArrowhead": "arrow"
		},
		{
			"type": "arrow",
			"version": 4520,
			"versionNonce": 620154606,
			"isDeleted": false,
			"id": "5rhoEy1jd5IYwCMkswHkh",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2549.1561594197,
			"y": 4776.215560714323,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#b2f2bb",
			"width": 129.3085760618028,
			"height": 0,
			"seed": 774726834,
			"groupIds": [
				"2wrwCb__lhHQ8CJtqbuf6"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1725547071569,
			"link": null,
			"locked": false,
			"startBinding": {
				"elementId": "oPxb9hrMOUNO9wrfeLxEE",
				"focus": 0.07235605887436078,
				"gap": 3.90038324745737
			},
			"endBinding": {
				"elementId": "qHeYQQZ7i6NX1bjJqjsxe",
				"focus": -0.030705092639214455,
				"gap": 1
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
					-129.3085760618028,
					0
				]
			]
		},
		{
			"type": "text",
			"version": 206,
			"versionNonce": 52640562,
			"isDeleted": false,
			"id": "xo6ZlviR",
			"fillStyle": "solid",
			"strokeWidth": 2,
			"strokeStyle": "solid",
			"roughness": 0,
			"opacity": 100,
			"angle": 0,
			"x": 2446.721667789843,
			"y": 4739.662335310232,
			"strokeColor": "#1e1e1e",
			"backgroundColor": "#b2f2bb",
			"width": 102.67999267578125,
			"height": 19.2,
			"seed": 445287410,
			"groupIds": [
				"2wrwCb__lhHQ8CJtqbuf6"
			],
			"frameId": null,
			"roundness": null,
			"boundElements": [],
			"updated": 1724917058925,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 3,
			"text": "message 수신",
			"rawText": "message 수신",
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "message 수신",
			"lineHeight": 1.2,
			"baseline": 15
		}
	],
	"appState": {
		"theme": "light",
		"viewBackgroundColor": "#ffffff",
		"currentItemStrokeColor": "#1e1e1e",
		"currentItemBackgroundColor": "#b2f2bb",
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
		"scrollX": -1774.7027499169208,
		"scrollY": -4151.918192727065,
		"zoom": {
			"value": 1.0554008235080758
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