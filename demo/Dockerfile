FROM openjdk:11-jdk
ARG JAR_FILE=builds/libs/*.jar
COPY ${JAR_FILE} app.jar
CMD ["java", "-jar", "app.jar"]
