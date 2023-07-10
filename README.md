# Docker-Assignment

                                Assignment 1 Question 
                                   (Spring App)

Create the desired steps in the Dockerfile to finish the deployment of the application.

The image for Java is adoptopenjdk/openjdk11:alpine-jre. This is an Alpine-based build which is smaller and more streamlined than the official image.

You need to navigate to /opt/app directory, then copy the jar file target/spring-boot-web.jar that contains the spring app to that directory.
The app is running on port 8080

Hints:
  -	To start the java spring boot application use the java -jar app.jar command.
