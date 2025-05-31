FROM openjdk:21-jdk-slim

LABEL authors="znaji"

#INSTALL curl:
RUN apt-get update && apt-get install -y curl && rm -rf /var/lib/apt/lists/*

COPY ./target/EazyBank-MS-config-server-0.0.1-SNAPSHOT.jar app.jar

ENTRYPOINT ["java", "-jar", "app.jar"]