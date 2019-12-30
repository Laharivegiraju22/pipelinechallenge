FROM openjdk:8

RUN echo 'Deploying jar on Server'

COPY /target/spring-boot-sample-atmosphere-1.4.0.BUILD-SNAPSHOT.jar usr/src/myapp

WORKDIR /usr/src/myapp

CMD ["java","-jar","spring-boot-sample-atmosphere-1.4.0.BUILD-SNAPSHOT.jar"]

EXPOSE 8080
