## Rion's API
이 문서는 테스트 API에 대해 기술합니다.
 
## 1. 이용 안내

 1. 서버간 통신은 보안을 위하여 HTTPS를 쓰도록 권장<br/>
 1. HTTPS를 통하여 API를 이용하는 서버는 유효한 공인인증서를 사용<br/>
 
## 2. 주의사항

 1. API 
 2. 회원
 3. 업무
 
## 3. 이용
#### 3.1. 앱 생성
자동응답 기능

1. [이슈](https://github.com/rionkims/MyOne/issues) 선택
2. 개인정보 수집 및 이용에 동의

##### *Error Table

| http status code | code |  comment |
| ---------------- | ---- |  ------- |
| 400 | 100 | bad request |
| 400 | 201 | wrong api key |
| 400 | 202 | wrong bot url |
| 503 | 203 | wrong message format |
| 408 | 204 | request timeout |
| 408 | 204 | wrong keyboard initialization |
| 400 | 301 | profile not found |
| 400 | 302 | user not found |
| 400 | 303 | not user friend |
| 400 | 400 | unsupported media type |


## *질의응답*
상단의 issue를 통해서 문의주시길 바랍니다.
- https://github.com/rionkims/MyOne/issues

* * *

***
