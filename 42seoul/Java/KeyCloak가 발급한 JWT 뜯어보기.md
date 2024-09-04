---
날짜: 2024-08-27
넘버: 
태그: 
출처: https://usmanshahid.medium.com/levels-of-access-control-through-keycloak-part-3-access-control-through-roles-and-tokens-a1744c04895e
aliases:
---
### 날짜:  2024-08-27 00:14

### 태그: #프로그래밍 #프로그래밍/보안 

>[!메모]
>

### 원문
---
# KeyCloak가 발급한 JWT 뜯어보기
```json
{
    "exp": 1596517043,
    "iat": 1596481043,
    "jti": "24690fd3-bf00-450f-8937-1893cea8bf8a",
    "iss": "http://localhost:8080/auth/realms/test",
    "aud": "account",
    "sub": "f33d74d4-a5ed-4da0-817c-503e75a81465",
    "typ": "Bearer",
    "azp": "my-test-client",
    "session_state": "f8530352-29b3-47f0-bfb5-914bc8b6536e",
    "acr": "1",
    "allowed-origins": [
        "/*"
    ],
    "realm_access": {
        "roles": [
            "offline_access",
            "uma_authorization"
        ]
    },
    "resource_access": {
        "account": {
            "roles": [
                "manage-account",
                "manage-account-links",
                "view-profile"
            ]
        }
    },
    "scope": "email profile",
    "email_verified": false,
    "preferred_username": "admin"
}
```
### realm_access
- 전역 
### resource_access
- 지역

---
### 생각(파생된 질문/생각)

### 출처
- https://usmanshahid.medium.com/levels-of-access-control-through-keycloak-part-3-access-control-through-roles-and-tokens-a1744c04895e

### 연결 문서 (연결 이유)
