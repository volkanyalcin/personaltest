FROM openjdk:8-jdk-alpine
VOLUME /tmp
EXPOSE 8080
ARG JAR_FILE=target/gs-spring-boot-docker-0.1.0.jar
ADD ${JAR_FILE} volkan-first-docker-demo.jar
ENTRYPOINT ["java","-jar","/volkan-first-docker-demo.jar"]