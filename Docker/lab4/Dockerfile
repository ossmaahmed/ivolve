FROM amazoncorretto:17-alpine3.22-full 

WORKDIR /app

COPY target/calculator.jar .


RUN addgroup -S appgroup && adduser -S appuser -G appgroup

RUN chown -R appuser:appgroup /app

USER appuser


CMD ["java", "-jar" ,"calculator.jar"]



