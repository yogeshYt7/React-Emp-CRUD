# Use the official OpenJDK image as a base image
FROM openjdk:latest

# Set the working directory in the container
WORKDIR /app/backend

# Copy the JAR file to the working directory
COPY ./emp.jar ./

# Expose port 8080
EXPOSE 8080

# Command to run the Java application
CMD ["java", "-jar", "emp.jar"]
