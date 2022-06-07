FROM openjdk:8
EXPOSE 8091
RUN mkdir -p /app/
ADD build/libs/service-customer-0.0.1-SNAPSHOT.jar /app/service-customer-0.0.1-SNAPSHOT.jar
COPY ${JAR_FILE} service-customer-0.0.1-SNAPSHOT.jar
ENTRYPOINT ["java", "-jar", "/app/service-customer-0.0.1-SNAPSHOT.jar"]