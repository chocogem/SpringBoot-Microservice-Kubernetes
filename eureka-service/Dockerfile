FROM openjdk:8-jdk-alpine
RUN apk --no-cache add curl
ARG JAR_FILE=target/*.jar
COPY ${JAR_FILE} /data/eureka-service.jar
ENTRYPOINT ["java","-jar","/data/eureka-service.jar"]