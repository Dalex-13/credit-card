
FROM adoptopenjdk/openjdk11:alpine-jre

ARG JAR_FILE=target/*.jar
COPY ${JAR_FILE} crediCard.jar
ENTRYPOINT ["java","-jar","/crediCard.jar"]
