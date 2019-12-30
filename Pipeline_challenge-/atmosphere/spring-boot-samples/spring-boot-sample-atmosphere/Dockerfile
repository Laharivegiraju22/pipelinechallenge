FROM tomcat:8.0

RUN echo 'Deploying War on Server'

COPY /var/lib/jenkins/workspace/pipelineChallenge/pipelinechallenge/Pipeline_challenge-/atmosphere/spring-boot-samples/spring-boot-sample-atmosphere/target/ spring-boot-sample-atmosphere-1.4.0.BUILD-SNAPSHOT.war
 usr/local/tomcat/webapps

CMD ["catalina.sh", "run"]

EXPOSE 8082

