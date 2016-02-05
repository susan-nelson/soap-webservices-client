HOW TO BUILD and RUN:
====================
This project depends on an installation of the following:
    for build, maven 3
        see maven.apache.org
    to run, java 8
        see oracle.com/technetwork/java/javase/downloads/index.html

To build and startup with embedded tomcat:
    cd  to root of project
    mvn clean spring-boot:run

    (this starts the client Application which calls the web service for a hard coded zip code,
        prints the response and exits).

To create an executable jar:
    cd  to root of project
    mvn clean package
    (creates soap-webservices-client-0.0.1-SNAPSHOT.jar)

To execute jar from the command line at root of project:
    java -jar target/soap-webservices-client-0.0.1-SNAPSHOT.jar <zipcode>

    (this starts the client Application which calls the web service, prints the response and exits).


