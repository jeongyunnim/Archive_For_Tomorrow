---
날짜: '"2023-11-15"'
넘버: 
태그: 42subject
출처: https://docs.docker.com/compose/compose-file/05-services/
aliases:
---
### 날짜  2023-11-15 19:14

### 태그: #42subject 

>[!메모]
> 이 옵션을 도대체 어떻게 찾은 것인가

### 원문
---
### [image](https://docs.docker.com/compose/compose-file/05-services/#image)

`image` specifies the image to start the container from. `image` must follow the Open Container Specification [addressable image formatopen_in_new](https://github.com/opencontainers/org/blob/master/docs/docs/introduction/digests.md), as `[<registry>/][<project>/]<image>[:<tag>|@<digest>]`.

```yml
    image: redis
    image: redis:5
    image: redis@sha256:0ed5d5928d4737458944eb604cc8509e245c3e19d02ad83935398bc4b991aac7
    image: library/redis
    image: docker.io/library/redis
    image: my_private.registry:5000/redis
```

If the image does not exist on the platform, Compose attempts to pull it based on the `pull_policy`. If you are also using the [Compose Build Specification](https://docs.docker.com/compose/compose-file/build/), there are alternative options for controlling the precedence of pull over building the image from source, however pulling the image is the default behavior.

`image` may be omitted from a Compose file as long as a `build` section is declared. If you are not using the Compose Build Specification, Compose won't work if `image` is missing from the Compose file.

### [pull_policy](https://docs.docker.com/compose/compose-file/05-services/#pull_policy)

`pull_policy` defines the decisions Compose makes when it starts to pull images. Possible values are:

- `always`: Compose always pulls the image from the registry.
- `never`: Compose doesn't pull the image from a registry and relies on the platform cached image. If there is no cached image, a failure is reported.
- `missing`: Compose pulls the image only if it's not available in the platform cache. This is the default option if you are not also using the [Compose Build Specification](https://docs.docker.com/compose/compose-file/build/). `if_not_present` is considered an alias for this value for backward compatibility.
- `build`: Compose builds the image. Compose rebuilds the image if it's already present.

If `pull_policy` and `build` are both present, Compose builds the image by default. This behavior may be overridden in the toolchain, depending on the implementation.


---
### 생각(파생된 질문/생각)

### 출처
- https://docs.docker.com/compose/compose-file/05-services/

### 연결 문서 (연결 이유)
