FROM amazoncorretto:8u432-al2023

EXPOSE 8080

COPY . .

RUN ./mvnw package

CMD java -jar ./target/docker-example-1.1.3.jar

