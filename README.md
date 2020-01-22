# trams-parent-pom
TraMS is a Transport Management Simulator. It is a platform consisting of microservices which can be used together or independently to simulate operations of a transport operator/company/organisation. The Parent POM provides a basis for this platform containing the dependencies 

## Version 1.0.1 with Java 13 & Spring Boot 2.2.3
This POM can be used as a Parent POM for any microservice for the TraMS Platform. It uses Spring Boot 2, Java 13, Eureka Service Discovery and Continuous Integration. To use the POM, you must download it manually (see assets on the right-hand side of the screen) and install it into your Maven repository. Then you can use the POM as a Parent POM by adding the following code to your POM:

```
<parent>
	<groupId>de.davelee.trams</groupId>
	<artifactId>trams-parent-pom</artifactId>
	<version>1.0.1</version>
</parent>
```
