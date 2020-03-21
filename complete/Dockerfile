FROM openjdk:8-jdk-alpine

ENV SERVER_PORT=8080

EXPOSE 8080

USER 1001

COPY build/libs/actuator-service-0.0.1-SNAPSHOT.jar app.jar

ENTRYPOINT ["java","-jar","/app.jar"]

