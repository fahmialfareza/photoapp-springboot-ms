FROM openjdk:18-jdk-alpine

VOLUME /tmp
COPY target/PhotoAppApiGateway-0.0.1-SNAPSHOT.jar ApiGateway.jar
ENTRYPOINT ["java", "-jar", "ApiGateway.jar"]