FROM openjdk:19-alpine
ARG JAR_FILE=build/libs/*.jar
COPY ${JAR_FILE} customer-service.jar
ENTRYPOINT ["java","-jar","/customer-service.jar"]