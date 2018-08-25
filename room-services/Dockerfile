FROM java:8
EXPOSE 8101
ADD /target/room-services-0.0.1-SNAPSHOT.jar room-services.jar
ENTRYPOINT ["java","-jar","room-services.jar"]