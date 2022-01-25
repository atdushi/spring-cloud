#FROM java:8
FROM java:8-jre
EXPOSE 8761
ADD ./target/eureka-service.jar eureka-service.jar
ENTRYPOINT ["java", "-jar", "/eureka-service.jar"]