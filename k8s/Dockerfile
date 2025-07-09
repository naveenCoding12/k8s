FROM openjdk:17
RUN mkdir /app
WORKDIR /app
COPY target/*.jar /app/app.jar
EXPOSE 9090
ENTRYPOINT ["java", "-jar", "/app/app.jar"]
