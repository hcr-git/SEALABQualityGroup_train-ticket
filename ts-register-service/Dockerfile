FROM eclipse-temurin:8-jdk-noble


ADD ./target/ts-register-service-1.0.jar /app/
CMD ["java", "-Xmx200m", "-jar", "/app/ts-register-service-1.0.jar"]

EXPOSE 12344