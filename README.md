# FIFA
FIFA Ratings API on CRUD using Spring for Java<br /><br />

Dependencies Used:<br />
Spring Data JPA<br />
Rest Repositories<br />
HAL Browser<br />
H2 Database<br /><br />

#######<br />
H2Database application properties:<br />
spring.datasource.url=jdbc:h2:mem:test/db<br />
<i>Note the in-memory database^</i><br />
spring.jpa.hibernate.ddl-auto=create-drop<br /><br />

#######<br />
Problem to solve:<br />
H2 supports JBDC API and R2DBC access and currently throws a Syntax error:<br />
org.h2.jdbc.JdbcSQLSyntaxErrorException: Table not found on SQL.
