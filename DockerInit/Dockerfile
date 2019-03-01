FROM alpine:latest
ADD HolaMundo.class HolaMundo.class
RUN apk --update add openjdk8-jre	
ENTRYPOINT ["java", "-Djava.security.egd=file:/dev/./urandom", "HolaMundo"]
