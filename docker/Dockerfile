# Use JDK Corretto 17 as the base image
FROM amazoncorretto:17.0.12

# Set the working directory in the container
WORKDIR /app

# Copy the JAR file to the container
ARG JAR_FILE
COPY ${JAR_FILE} /app.jar