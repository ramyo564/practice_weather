resources/application.properties

spring.datasource.driver-class-name=com.mysql.cj.jdbc.Driver
spring.datasource.url=jdbc:mysql://localhost:3306/project?serverTimezone=UTC&characterEncoding=UTF-8
spring.datasource.username={root_id}
spring.datasource.password={password}
spring.jpa.show-sql=true
spring.jpa.database=mysql
openweathermap.key={API_KEY}
logging.config=classpath:logback-spring.xml
