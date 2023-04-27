FROM openjdk:8-jdk-alpine

# artifact path
#ARG artifact=target/spring-boot-web.jar

WORKDIR /opt/app

COPY . .

# This should not be changed
ENTRYPOINT ["java","-jar","app.jar"]
