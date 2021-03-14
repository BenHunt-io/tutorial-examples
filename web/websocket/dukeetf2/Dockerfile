FROM azul/zulu-openjdk-alpine:15.0.2

WORKDIR /app
COPY /target /app

ENTRYPOINT ["java"]
CMD ["-jar", "dukeetf2-microbundle.jar", "--port", "8080"]