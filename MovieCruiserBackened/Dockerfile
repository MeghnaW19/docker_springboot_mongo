FROM java:8-jre
ADD ./target/MovieCruiserServer-0.0.1-SNAPSHOT.jar /usr/src/MovieCruiserServer-0.0.1-SNAPSHOT.jar
WORKDIR usr/src
ENTRYPOINT ["java","-jar", "MovieCruiserServer-0.0.1-SNAPSHOT.jar"]
