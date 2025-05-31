FROM openjdk:21-jdk-slim

LABEL authors="znaji"

COPY ./target/loans-0.0.1-SNAPSHOT.jar app.jar

ENTRYPOINT ["java", "-jar", "app.jar"]