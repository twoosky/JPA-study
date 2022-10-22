# JPA-study
## JPA 소개

**JPA 소개**  
* JPA란
  * Java Persistence API
  * 자바 진영의 `ORM` 기술 표준
* ORM
  * Object-relational mapping(객체 관계 매핑)
  * 객체는 객체대로 설계, 관계형 데이터베이스는 관계형 데이터베이스대로 설계
  * ORM 프레임워크가 중간에서 매핑
* JPA 동작
  * JPA는 애플리케이션과 JDBC 사이에서 동작한다.  
  `1`. JAVA 애플리케이션에서 JPA에게 명령   
  `2`. JPA가 SQL을 만들어 JDBC API를 사용해 DB에 전송    
  `3`. DB로부터 반환된 결과를 JAVA 애플리케이션에서 사용
  <img src="https://user-images.githubusercontent.com/50009240/197345390-f7c3eeb3-6f49-4e88-a12c-55e40f19ec20.png" width="500" height="200">
