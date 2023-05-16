# Base image with Java 8
FROM openjdk:8-jdk-alpine

# Set the working directory
WORKDIR /app

# Copy the Maven wrapper files (mvnw and .mvn) to the container
COPY mvnw .
COPY .mvn .mvn

# Copy the project files to the container
COPY src src
COPY pom.xml .

# Install Maven
RUN apk add --no-cache maven

# Build the project with Maven
RUN ./mvnw package

# Set the command to run the application
CMD ["java", "-jar", "./target/docker-example-1.1.3.jar"]

# Expose port 8080 to access the application
EXPOSE 8080
