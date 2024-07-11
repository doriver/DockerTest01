FROM bellsoft/liberica-openjdk-alpine:17
ARG JAR_FILE=*.jar
COPY ${JAR_FILE} app.jar
RUN mkdir -p /upload/images
ENTRYPOINT ["java","-jar","/app.jar"]