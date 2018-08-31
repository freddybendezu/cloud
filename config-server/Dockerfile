FROM java:8
EXPOSE 9000
ADD /target/config-server-0.0.1-SNAPSHOT.jar config-server.jar
ENTRYPOINT ["java","-jar","config-server.jar"]