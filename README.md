# FIFA
FIFA Ratings API on CRUD using Spring for Java

Dependencies Used:
Spring Data JPA
Rest Repositories
HAL Browser
H2 Database

#######
H2Database application properties:
spring.datasource.url=jdbc:h2:mem:test/db
spring.jpa.hibernate.ddl-auto=create-drop

#######
Problem to solve:
H2 supports JBDC API and R2DBC access and currently throws a Syntax error:
org.h2.jdbc.JdbcSQLSyntaxErrorException: Table not found on SQL.
