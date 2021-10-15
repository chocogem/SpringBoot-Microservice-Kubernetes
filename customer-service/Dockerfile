FROM openjdk:8-jdk-alpine
ARG JAR_FILE=target/*.jar
COPY ${JAR_FILE} /data/customer-service.jar
ENTRYPOINT ["java","-jar","/data/customer-service.jar"]