FROM openjdk:17-jdk

EXPOSE 8080

WORKDIR /app
COPY target/app.jar app.jar

ENTRYPOINT ["java", "-jar", "app.jar"]
