---
날짜: '"2023-12-16"'
넘버: 
태그: 프로그래밍
출처: 
aliases:
---
### 날짜  2023-12-16 17:58

### 태그:

>[!메모]
>

### 원문
---
# Server-Side Rendering
사용자에게 보여줄 페이지를 모두 구성하여 사용자에게 페이지를 보여주는 방식이다.
JSP/Servlet의 아키텍처에서 이 방식을 사용했다.

SSR을 사용하면 모든 데이터가 매핑된 서비스 페이지를 클라이언트에게 바로 보여줄 수 있다.
서버를 이용해 페이지를 구성하기 때문에 클라이언트에서 구성하는 CSR(Client-Side Rendering)보다 페이지를 구성하는 속도는 늦지만 사용자에게 보여주는 콘텐츠 구성이 완료되는 시점은 빨라진다. 또한 [[SEO]](Serch engine optimization) 또한 쉽게 구성할 수 있다.

[[Single-Page Application|SPA]] 구성을 하기 위해서는 기본적으로 frontend와 backend 영역의 분리가 선행되어야 한다.

기존의 페이지 덩어리를 **CSR view** 영역과 **SSR view** 영역 그리고 **API**로 분리한다.
![[ft_transcendence.excalidraw#^group=C9cNPAzPmzEdD4g0bYTPV]]
## [[Node.js]] 기반의 SSR을 선택한 이유
- CSR의 문제를 해결할 수 있는 여러가지 렌더링 기법
	- [[Rendering on the Web]]
### 1. JavaScript를 최대한 활용할 수 있음.
일반적으로 클라이언트에서 작성한 코드의 일부는 서버에서도 동일한 로직으로 구성되는 경우가 많다.
개발의 난이도는 높아지나 생산성 측면에서는 SSR을 구축하는 것이 더 효율적이다.

블로그 개발팀은 React 기반의 SSR을 선택했다.
### 2. FE와 BE를 완전히 분리하여 생산성을 높일 수 있음.
SSR을 사용하면 FE와 BE 영역을 [[REST API]]를 통해 느슨하게 연결할 수 있다.

기존 CSR 페이지는 FE에서 개발하고 SSR 페이지는 BE에서 개발한다.
SSR 환경을 구축하면 페이지의 소유권이 온전히 FE에 존재하므로 페이지가 변경될 때마다 불필요한 커뮤니케이션을 하지 않아도 된다.

백엔드에서도 API 개발과 데이터 활용에 더 집중할 수 있어 서비스 품질을 더 높일 수 있다는 장점이 있다.

![[Excalidraw/ft_transcendence.excalidraw.md#^group=AGkp07icIHablqN1Pxgih]]





---
### 생각(파생된 질문/생각)

### 출처
- https://d2.naver.com/helloworld/7804182
- SSR과 CSR의 차이
	- https://medium.com/walmartlabs/the-benefits-of-server-side-rendering-over-client-side-rendering-5d07ff2cefe8
- https://web.dev/articles/rendering-on-the-web?hl=en
### 연결 문서 (연결 이유)
- [[Single-Page Application|SPA]]