FROM hub.mooc.com:8080/micro-service/openjdk:8-jre
MAINTAINER qingbao.ho@gmail.com

COPY target/user-edge-service-1.0-SNAPSHOT.jar /user-edge-service.jar
ENTRYPOINT ["java", "-jar", "/user-edge-service.jar"]