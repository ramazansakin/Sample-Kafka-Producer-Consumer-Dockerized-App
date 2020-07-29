FROM openjdk:8-jdk-alpine

MAINTAINER Ramazan Sakin <ramazansakin63@gmail.com>
ADD target/*.jar kafka-consumer-service.jar

ENTRYPOINT ["java","-jar","/kafka-consumer-service.jar"]