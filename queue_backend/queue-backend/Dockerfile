# Use OpenJDK base image
FROM openjdk:17

# Set metadata
LABEL maintainer="kotak"

# Copy the generated jar into the container
COPY target/queue-backend-0.0.1-SNAPSHOT.jar app.jar

# Expose the port (optional for Render, but good practice)
EXPOSE 8080

# Run the JAR
ENTRYPOINT ["java", "-jar", "/app.jar"]
