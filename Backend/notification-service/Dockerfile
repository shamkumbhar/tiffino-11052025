FROM eclipse-temurin:17-jdk-alpine 
WORKDIR /app
COPY target/notification-service-0.0.1-SNAPSHOT.jar notification-service-0.0.1-SNAPSHOT.jar
EXPOSE 8980
CMD ["java", "-jar", "notification-service-0.0.1-SNAPSHOT.jar"]
