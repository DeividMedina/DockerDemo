FROM alpine:latest
RUN apk --update add openjdk8-jre
COPY docker-Hola-Mundo-example.jar app.jar
ENTRYPOINT ["java", "-Djava.security.egd=file:/dev/./urandom", "-jar", "app.jar"]

