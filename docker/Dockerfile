FROM amazoncorretto:17.0.14-al2023-headless
# properties
ARG JAR_FILE=target/java-docker-app.jar
ARG JAR_LIB_FILE=target/lib/
# change working directory # cd path-to-your-working-directory
WORKDIR /app/docker-builds
# copy target/java-docker-app.jar path-to-your-working-directory/app.jar
COPY ${JAR_FILE} app.jar
# java -jar path-to-your-working-directory/app.jar
ENTRYPOINT ["java","-jar","app.jar"]