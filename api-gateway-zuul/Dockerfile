FROM hub.mooc.com:8080/micro-service/openjdk:8-jre
MAINTAINER qingbao.ho@gmail.com

COPY target/api-gateway-zuul-1.0-SNAPSHOT.jar /api-gateway-zuul.jar
ENTRYPOINT ["java", "-jar", "/api-gateway-zuul.jar"]