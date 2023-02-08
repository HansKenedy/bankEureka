FROM openjdk:19
VOLUME /tmp
EXPOSE 8761
ADD ./target/eureka-server-0.0.1-SNAPSHOT-exec.jar ms-eureka-server.jar
ENTRYPOINT ["java","-jar","ms-eureka-server.jar"]