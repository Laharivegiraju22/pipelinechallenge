FROM openjdk:8

RUN mkdir -p /usr/src/myapp

COPY /target/spring-boot-sample-atmosphere-1.4.0.BUILD-SNAPSHOT.jar usr/src/myapp

WORKDIR /usr/src/myapp

EXPOSE 8080

CMD ["java","-jar","spring-boot-sample-atmosphere-1.4.0.BUILD-SNAPSHOT.jar"]


