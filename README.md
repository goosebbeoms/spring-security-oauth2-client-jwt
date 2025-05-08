# spring-security-oauth2-client-jwt

- Spring Security OAuth2 Client JWT 방식 구현 개념 학습 및 실습 코드 업로드용 리포지토리
- 구현 시 특징
  - 인증 : 네이버 소셜 로그인, 구글 소셜 로그인 (코드 방식) 후 JWT 발급
  - 인가 : JWT 방식을 통한 경로별 접근 권한
  - 인증 정보는 DB 저장 후 추가 정보 기입
  - 소셜 로그인을 통해 인증 받은 데이터는 서비스 데이터베이스에 저장을 한 뒤 관리를 진행함
  - JWT의 경우 단일 토큰으로 진행함
- 동작 원리
  - 출처 : [https://www.devyummi.com/page?id=669296ed4b5dc5675c8737be](https://www.devyummi.com/page?id=669296ed4b5dc5675c8737be)
    ![구조도](./structure.jpg)
- 참고 자료
  - YOUTUBE : [개발자 유미](https://youtube.com/playlist?list=PLJkjrxxiBSFALedMwcqDw_BPaJ3qqbWeB&si=hRVpo38D6OhyD69s)
  - Site : [개발자 유미](https://www.devyummi.com/page?id=669296ed4b5dc5675c8737be)
  - Docs : [spring.io > Spring Security Docs](https://docs.spring.io/spring-security/reference/index.html)
