FROM openjdk:8-jdk-alpine
ARG JAR_FILE=target/*.jar
COPY ${JAR_FILE} /data/gateway.jar
ENTRYPOINT ["java","-jar","/data/gateway.jar"]