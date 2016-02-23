FROM java:8
VOLUME /tmp
ADD ./target/spring-cloud-config-client-0.1.0.jar app.jar
RUN bash -c 'touch /app.jar'
EXPOSE 8002
ENTRYPOINT ["java","-Djava.security.egd=file:/dev/./urandom","-jar","/app.jar"]