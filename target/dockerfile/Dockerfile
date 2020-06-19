FROM openjdk

VOLUME /tmp
ADD maven/rest-service-0.0.1-SNAPSHOT.jar rest-service-0.0.1-SNAPSHOT.jar
RUN sh -c 'touch /rest-service-0.0.1-SNAPSHOT.jar'
ENTRYPOINT ["java","-Djava.security.egd=file:/dev/./urandom","-jar","/rest-service-0.0.1-SNAPSHOT.jar"]

EXPOSE 8080