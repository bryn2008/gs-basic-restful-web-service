FROM frolvlad/alpine-oraclejdk8:slim
VOLUME /tmp
ADD gs-basic-restful-web-server-0.0.1-SNAPSHOT.jar gs-basic-restful-web-service.jar
ENTRYPOINT ["java","-Djava.security.egd=file:/dev/./urandom","-jar","/gs-basic-restful-web-service.jar"]