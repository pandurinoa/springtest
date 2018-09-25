# FROM openjdk:10-jre-slim
FROM openjdk:8-jdk-alpine
EXPOSE 8080
EXPOSE 2181
EXPOSE 9092
EXPOSE 5672
EXPOSE 15672
ADD ./source-0.0.1-SNAPSHOT.jar source-0.0.1-SNAPSHOT.jar
ENTRYPOINT ["java", "-jar", "source-0.0.1-SNAPSHOT.jar"]