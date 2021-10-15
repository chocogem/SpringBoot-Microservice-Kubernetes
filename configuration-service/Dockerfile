FROM openjdk:8-jdk-alpine
ARG JAR_FILE=target/*.jar
COPY ${JAR_FILE} /data/configuration-service.jar
ENTRYPOINT ["java","-jar","/data/configuration-service.jar"]