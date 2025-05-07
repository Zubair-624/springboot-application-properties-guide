# Database Configuration
spring.datasource.url=jdbc:mysql://localhost:3306/ems
spring.datasource.username=
spring.datasource.password=
spring.datasource.driver-class-name=com.mysql.cj.jdbc.Driver

# JPA and Hibernate Configuration
spring.jpa.hibernate.ddl-auto=update
spring.jpa.show-sql=true
spring.jpa.properties.hibernate.format_sql=true

##Use one of the two properties below
spring.jpa.database-platform=org.hibernate.dialect.MySQL8Dialect
#spring.jpa.properties.hibernate.dialect=org.hibernate.dialect.MySQL8Dialect