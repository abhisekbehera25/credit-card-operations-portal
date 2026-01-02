FROM openjdk:17

WORKDIR /app
COPY ./target/credit-service.jar /app
EXPOSE 8082
CMD ["java", "-jar", "credit-service.jar"]