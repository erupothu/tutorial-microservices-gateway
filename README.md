# tutorial-microservices-gateway

<strong>Gateway Server</strong>

spring-cloud-starter-netflix-hystrix (for circuit break and fallback)<br>
spring-cloud-starter-gateway (centralised routing to connect to microservices)<br>
spring-cloud-starter-netflix-eureka-client (Discovery and registration for microservices)<br>

<strong>Eureka Server</strong>

spring-cloud-starter-netflix-eureka-server (Discovery and registration for microservices)<br>

<strong>Book and Student microservices</strong>

spring-boot-starter-test (integration testing)<br>
hazelcast (for cacheing usefull when too mainy request to same api ex: reports)<br>
spring-boot-starter-data-jpa (framwork for object Relation Mapping)<br>
com.h2database (inmemory database)<br>
spring-boot-starter-actuator (for detailed information about the microservice)<br>
spring-cloud-starter-openfeign ( for load balancing, circuitbreak, fallback and remote calls to microservices)<br>
spring-cloud-starter-netflix-eureka-client (Discovery and registration for microservices)<br>
springdoc-openapi-ui ( microservice documentation api docs)<br><br>
org.projectlombok (for boiler plate code by removing most of code like setters, getters, constructors etc)<br>
spring-session-core, spring-session-jdbc (for session management)<br>

<strong>Extra:</strong>

Exception Handling<br>
AOP<br>
Interceptors<br>
Cors config<br>

<strong>install mysql-server in ubuntu:</strong><br>
echo "mysql-server mysql-server/root_password password ThePassword@1" | sudo debconf-set-selections 
echo "mysql-server mysql-server/root_password_again password ThePassword@1" | sudo debconf-set-selections
sudo apt-get install mysql-server

mysql -u root -p
ThePassword@1






