# spring-boot-microservice-eureka-naming-server
 Eureka Naming server for load Balancing
 
 <img src="https://github.com/nikhilz/spring-boot-microservice-eureka-naming-server/blob/master/src/main/resources/Static/images/Spring-Boot-Microservice-6-EurekaNamingServer-Deployment.png">

Forex Service: https://github.com/nikhilz/spring-boot-microservice-forex-service

Currency Conversion : https://github.com/nikhilz/spring-boot-microservice-currency-conversion

- Currency Conversion Micro Service (CCS) on 8100
- Two instances of Forex MicroService on 8000 and 8001
- Eureka Server launched

Now you would see that the requests to CCS would get distributed between the two instances of Forex Microservice by Ribbon through Eureka.

<img src="https://github.com/nikhilz/spring-boot-microservice-eureka-naming-server/blob/master/src/main/resources/Static/images/Spring-Boot-Microservice-7-Eureka-Sequence-Diagram.png">
