FROM openjdk:8-jdk-alpine
ARG JAR_FILE=target/*.jar
COPY ${JAR_FILE} /data/eureka-service.jar
ENTRYPOINT ["java","-jar","/data/eureka-service.jar"]