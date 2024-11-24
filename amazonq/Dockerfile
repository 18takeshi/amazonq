FROM openjdk:24-jdk
WORKDIR /app
COPY build/libs/*.jar /app/app.jar
EXPOSE 8081
ENTRYPOINT ["java", "-jar", "/app/app.jar"]