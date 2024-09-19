FROM amazoncorretto:17
LABEL authors="leonardogloria2"
WORKDIR /app
COPY ./docker/app.jar app.jar
EXPOSE 8091
ENTRYPOINT ["java", "-jar", "app.jar"]