For this project



✨  appliaction.properties file

spring.datasource.url= jdbc:mysql://localhost:3306/swastha3?createDatabaseIfNotExist=true
spring.datasource.username=root
spring.datasource.password=......

spring.jpa.hibernate.ddl-auto=update
spring.jpa.properties.hibernate.format_sql=true
spring.jpa.show-sql=true

spring.jpa.properties.hibernate.dialect = org.hibernate.dialect.MySQL8Dialect

spring.mvc.pathmatch.matching-strategy=ant-path-matcher
spring.mail.host=smtp.gmail.com
spring.mail.port=587
spring.mail.username=  .....@gmail.com
spring.mail.password= ............. ( we won't enter the real password ......After the two step authentication process generate the password key) 
spring.mail.properties.mail.smtp.auth=true
spring.mail.properties.mail.smtp.starttls.enable=true



✨  For this project will use dependencies like 

1. Spring Web    Web
Build web, including RESTful, applications using Spring MVC. Uses Apache Tomcat as the default embedded container.

2. Spring Data JPA    SQL
Persist data in SQL stores with Java Persistence API using Spring Data and Hibernate.

3. MySQL Driver SQL
MySQL JDBC driver.

4. Spring Boot DevTools Developer Tools
Provides fast application restarts, LiveReload, and configurations for enhanced development experience.




