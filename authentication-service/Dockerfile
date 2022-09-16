FROM openjdk:11
ADD ./target/authentication-service-0.0.1-SNAPSHOT.jar /usr/src/authentication-service-0.0.1-SNAPSHOT.jar
EXPOSE 8095
WORKDIR usr/src
ENTRYPOINT ["java","-jar", "authentication-service-0.0.1-SNAPSHOT.jar"]