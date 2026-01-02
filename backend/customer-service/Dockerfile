FROM openjdk:17

WORKDIR /app
COPY ./target/customer-service.jar /app
EXPOSE 8081
CMD ["java", "-jar", "customer-service.jar"]