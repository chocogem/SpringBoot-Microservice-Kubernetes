FROM openjdk:8-jdk-alpine
ARG JAR_FILE=target/*.jar
COPY ${JAR_FILE} /data/claim-service.jar
ENTRYPOINT ["java","-jar","/data/claim-service.jar"]