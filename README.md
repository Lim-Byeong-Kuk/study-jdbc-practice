# JDBC, DB Connection Pool 학습

### JDBC (Java Database Connectivity)
- 자바 애플리케이션에서 DB 프로그래밍을 할 수 있도록 도와주는 표준 인터페이스
- JDBC 인터페이스들을 구현한 구현체들은 각 데이터베이스 벤더 사들이 제공

### DBCP (Dtabase Connection Pool)
- 미리 일정량의 DB 커넥션을 생성해서 풀에 저장해 두고 있다가 HTTP 요청에 따라 필요할 때 풀에서 커넥션을 가져다 사용하는 기법
- 스프링 부트는 디폴터 커넥션 풀로 HikariCp 사용

### DtaSource
- 커넥션을 획득하기 위한 표준 인터페이스
- HikariCP의 DataSource 사용
