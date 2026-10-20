FROM maven:3.10-eclipse-temurin-17-alpine

WORKDIR /app

COPY . .

RUN addgroup -S appgroup && adduser -S appuser -G appgroup

RUN chown -R appuser:appgroup /app

USER appuser

RUN mvn package
CMD ["java" , "-jar" , "target/calculator.jar"]

EXPOSE 8080













