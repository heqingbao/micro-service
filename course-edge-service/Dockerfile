FROM hub.mooc.com:8080/micro-service/openjdk:8-jre
MAINTAINER qingbao.ho@gmail.com

COPY target/course-edge-service-1.0-SNAPSHOT.jar /course-edge-service.jar
ENTRYPOINT ["java", "-jar", "/course-edge-service.jar"]