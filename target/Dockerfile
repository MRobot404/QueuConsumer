FROM openjdk:8-jdk-alpine
COPY /lib /lib
COPY QueueConsumer-1.0-SNAPSHOT.jar app.jar
ENTRYPOINT ["java","-jar","/app.jar"]