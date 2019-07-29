FROM openjdk:8-jdk-alpine
VOLUME /apps
COPY ./Perseus/FinLeapTask.jar FinLeapTask.jar
ENTRYPOINT ["java","-Djava.security.egd=file:/dev/./urandom","-jar","/FinLeapTask.jar"]
