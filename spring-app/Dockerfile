FROM adoptopenjdk/openjdk11:alpine-jre
WORKDIR /opt/app
ADD target/spring-boot-web.jar ./
EXPOSE 8080
CMD [ "java","-jar","spring-boot-web.jar" ]