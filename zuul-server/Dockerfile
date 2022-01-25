FROM java:8-jre
EXPOSE 5555
ADD ./target/zuul-server.jar zuul-server.jar
ENTRYPOINT ["java", "-jar", "/zuul-server.jar"]