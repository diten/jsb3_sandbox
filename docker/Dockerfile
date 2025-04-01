FROM amazoncorretto:17.0.14-al2023-headless
WORKDIR /app/docker-builds
COPY spring-boot-app.jar app.jar
ENTRYPOINT ["java","-jar","app.jar"]
