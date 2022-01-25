FROM java:8-jre
EXPOSE 8081
ADD ./target/config-server.jar config-server.jar
ENTRYPOINT ["java", "-jar", "/config-server.jar"]