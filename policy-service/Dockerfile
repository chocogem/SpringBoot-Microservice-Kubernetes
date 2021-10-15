FROM openjdk:8-jdk-alpine
ARG JAR_FILE=target/*.jar
COPY ${JAR_FILE} /data/policy-service.jar
ENTRYPOINT ["java","-jar","/data/policy-service.jar"]