# 카카오 REST API 예제

이 프로젝트는 카카오 REST API를 사용하여 로그인 기능을 구현한 예제입니다.

## 설치 방법

1. 필요한 패키지 설치:

```bash
npm install
```

2. 카카오 개발자 센터에서 REST API 키 발급받기:

   - https://developers.kakao.com 에서 애플리케이션 등록
   - 발급받은 REST API 키를 `index.js` 파일의 `KAKAO_REST_API_KEY` 변수에 입력

3. 카카오 개발자 센터의 애플리케이션 설정에서 다음 항목 설정:
   - 플랫폼 > Web > 사이트 도메인에 `http://localhost:3000` 추가
   - 카카오 로그인 > Redirect URI에 `http://localhost:3000/oauth` 추가

## 실행 방법

```bash
npm start
```

서버가 실행되면 `http://localhost:3000`으로 접속하여 카카오 로그인을 테스트할 수 있습니다.
