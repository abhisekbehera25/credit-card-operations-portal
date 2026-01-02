FROM openjdk:17

WORKDIR /app
COPY ./target/auth-service.jar /app
EXPOSE 8084
CMD ["java", "-jar", "auth-service.jar"]