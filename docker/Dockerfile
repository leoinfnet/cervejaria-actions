FROM amazoncorretto:17
LABEL authors="leonardogloria2"
WORKDIR /app
RUN echo "O diretório de trabalho atual é:" && pwd
COPY app.jar app.jar
EXPOSE 8091
ENTRYPOINT ["java", "-jar", "app.jar"]