FROM amazoncorretto:17.0.14-al2023-headless
ARG JAR_FILE=/target/spring-boot-app.jar
WORKDIR /app/docker-builds
COPY ${JAR_FILE} app.jar
ENTRYPOINT ["java","-jar","app.jar"]
