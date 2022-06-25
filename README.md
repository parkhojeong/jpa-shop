### [실전! 스프링 부트와 JPA 활용1 - 웹 애플리케이션 개발](https://www.inflearn.com/course/%EC%8A%A4%ED%94%84%EB%A7%81%EB%B6%80%ED%8A%B8-JPA-%ED%99%9C%EC%9A%A9-1/dashboard)

### H2 데이터베이스 파일 생성 방법
- http://localhost:8082 접속
- `jdbc:h2:~/jpashop` 경로로 JDBC URL에 입력하여 접속 (최소 한번, 세션키 유지한 상태로 실행)
- `~/jpashop.mv.db` 파일 생성 확인
- 이후 부터는 `jdbc:h2:tcp://localhost/~/jpashop` 경로를 JDBC URL에 입력해 접속
