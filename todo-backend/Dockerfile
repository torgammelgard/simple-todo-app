FROM openjdk:17-jdk-slim
WORKDIR /app
COPY ./build/libs/todo-backend-0.0.1-SNAPSHOT.jar backend.jar
EXPOSE 8080
ENTRYPOINT ["java", "-jar", "backend.jar"]
