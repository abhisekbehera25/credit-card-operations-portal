FROM openjdk:17

WORKDIR /app
COPY ./target/transaction-service.jar /app
EXPOSE 8083
CMD ["java", "-jar", "transaction-service.jar"]