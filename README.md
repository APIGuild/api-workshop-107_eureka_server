# api-workshop-107_eureka_server

Build Eureka-Server

1.add Eureka-Server dependencies

	compile('org.springframework.cloud:spring-cloud-starter-eureka-server')
	compile('org.springframework.boot:spring-boot-starter-actuator')
	compile('org.springframework.boot:spring-boot-starter-aop')
	compile('org.springframework.boot:spring-boot-starter-web')

2.add annotations on Application class
   
     @SpringBootApplication
     @EnableEurekaServer
     
3.config application properties
    
     server.port=10000
     spring.application.name=eureka-server
     
     eureka.client.register-with-eureka=false
     eureka.client.fetch-registry=false
     eureka.client.service-url.defaultZone=http://localhost:10000/eureka/
    
6.Eureka-Server Cluster

    SOON...
	
	


