FROM openjdk:17

RUN mkdir /app

WORKDIR /app

COPY target/ZLogService-0.0.1-SNAPSHOT.jar .

EXPOSE 9191

ENTRYPOINT ["java", "-jar", "ZLogService-0.0.1-SNAPSHOT.jar"]
