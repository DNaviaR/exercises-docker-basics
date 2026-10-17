FROM amazoncorretto:8

WORKDIR /usr/src/app

COPY . .

# Build the Spring application
RUN ./mvnw package

# Expose the default Spring Boot port
EXPOSE 8080

# Command to run the application
CMD ["java", "-jar", "./target/docker-example-1.1.3.jar"]
