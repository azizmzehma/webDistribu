FROM openjdk:17 AS build

# Set the working directory
WORKDIR /app

# Copy the built JAR file from the microclient/target folder into the image
COPY eureka/target/*.jar app.jar

# Expose the application port
EXPOSE 8090

# Run the application
ENTRYPOINT ["java", "-jar", "app.jar"]
