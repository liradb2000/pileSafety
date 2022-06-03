---
sidebar_label: "로그인"
sidebar_position: 0
---

# 로그인

## 1. 이메일을 통한 로그인

1. 가입된 이메일 주소를 입력
1. 입력한 이메일 주소로 전송된 인증번호를 입력

![login](/img/login/process.gif)



## 2. 지문 또는 FaceID를 통한 로그인

### 1. 기기등록

우선 로그인 후 기기등록을 위한 본인 확인이 진행됩니다. 본인 확인 방식은 운영체제, 기기 별로 다를 수 있습니다.

![authn](/img/login/webauthn.gif)

### 2. 로그인

1. 가입된 이메일 주소를 입력
1. 등록된 생체 정보 인증

![authnlogin](/img/login/webauthnlogin.gif)

:::warning
다른기기에서 로그인 시 기존 로그인했던 기기에서는 로그아웃됩니다.
:::

:::danger
로그인 정보, 임시저장 정보는 브라우저에 저장됩니다. 클리너 프로그램등의 사용으로 정보가 소멸될 수 있습니다.
:::
