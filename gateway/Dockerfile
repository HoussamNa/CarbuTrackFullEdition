FROM openjdk:17
WORKDIR /app
COPY target/gateway-0.0.1-SNAPSHOT.jar /app/gateway.jar
EXPOSE 8888
ENTRYPOINT ["java", "-jar", "/app/gateway.jar"]
