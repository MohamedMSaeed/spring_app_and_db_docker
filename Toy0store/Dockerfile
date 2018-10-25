FROM openjdk:8-jdk-alpine
COPY Toy0Store.jar app.jar
ENTRYPOINT ["java","-Djava.security.egd=file:/dev/./urandom","-jar","/app.jar"]
