# Use an official OpenJDK runtime as a parent image
FROM openjdk:17-jdk

# Set the working directory to /app
WORKDIR /app

# Copy the current directory contents into the container at /app
COPY . /app

# Build the Java application (adjust the build command based on your project)
RUN ./mvnw clean install

# Make port 8080 available to the world outside this container
EXPOSE 8080

# Run app.jar when the container launches
CMD ["java", "-jar", "target/app.jar"]
