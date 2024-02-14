FROM openjdk:17-jdk

EXPOSE 8080

WORKDIR /app

# Copy the JAR file from the Maven build target directory to the current working directory inside the container
COPY ./target/app.jar app.jar

ENTRYPOINT ["java", "-jar", "app.jar"]
