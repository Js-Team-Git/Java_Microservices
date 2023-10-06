FROM openjdk:17

RUN mkdir /app

WORKDIR /app

COPY target/ZDepartmentService-0.0.1-SNAPSHOT.jar ZDepartmentService-0.0.1-SNAPSHOT.jar

EXPOSE 8080

ENTRYPOINT ["java", "-jar", "ZDepartmentService-0.0.1-SNAPSHOT.jar"]
