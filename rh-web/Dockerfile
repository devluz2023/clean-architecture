# Use an OpenJDK 8 image as base
FROM openjdk:8-jdk-alpine

# Set the working directory inside the container
WORKDIR /app

# Copy the compiled JAR file into the container
COPY ./target/rh-web-1.0.jar /app/rh-web-1.0.jar

# Command to run the application
CMD ["java", "-jar", "rh-web-1.0.jar"]
