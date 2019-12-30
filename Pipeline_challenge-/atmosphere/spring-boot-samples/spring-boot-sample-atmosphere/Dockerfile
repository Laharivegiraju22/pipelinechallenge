FROM tomcat:8.0

RUN echo 'Deploying War on Server'

COPY /target/spring-boot-sample-atmosphere-1.4.0.BUILD-SNAPSHOT.jar usr/src/myapp

CMD ["java","-jar","spring-boot-sample-atmosphere-1.4.0.BUILD-SNAPSHOT.jar"]

EXPOSE 8080
