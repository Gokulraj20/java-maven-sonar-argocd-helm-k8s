FROM openjdk:8-jdk-alpine

# Simply the artifact path
ARG artifact=target/spring-boot-web.jar

WORKDIR /opt/app

COPY ${artifact} .

# This should not be changed
ENTRYPOINT ["java","-jar","spring-boot-web.jar"]
