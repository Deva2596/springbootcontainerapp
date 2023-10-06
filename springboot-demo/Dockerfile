# Official OpenJDK runtime as a parent image
FROM openjdk:11-jre-slim

# Setting the working directory in the container
WORKDIR /app

# Copy the JAR file built by Maven into the container
COPY target/springboot-demo-0.0.1-SNAPSHOT.jar ./springbootcontainerapp.jar

# Expose the port that your Spring Boot application will run on
EXPOSE 8080

# Define the command to run your application
CMD ["java", "-jar", "springbootcontainerapp.jar"]
