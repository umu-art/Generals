FROM bellsoft/liberica-openjdk-alpine:latest
LABEL authors="vikazeni"
COPY /g-core/target/g-core-0.0.1-SNAPSHOT.jar /opt/app.jar
ENTRYPOINT ["java", "-jar", "/opt/app.jar"]
