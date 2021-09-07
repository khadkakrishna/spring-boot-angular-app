# spring-boot-angular-app
## Integration of Spring-Boot and Angular
This application is created to show the integration of spring boot and angular. Usually Spring boot application runs at `http://localhost:8080` while angular application `http://localhost:4200`.

To create a jar run either of following command: 

`mvn clean package` or `mvn clean install` this will create a jar at *target/SpringAngularApplication-0.0.1-SNAPSHOT.jar*

> The main difference between the “mvn package” and “mvn install” commands is that mvn package command will compile the source and will package it in its distributable formats, such as a JAR or WAR. The mvn install command, however, additionally to compiling the source code and packaging it into a JAR or a WAR, it will also install the package into the local repository, for use as a dependency in other projects locally.

To deploy the jar run the following command:

`java -jar target/SpringAngularApplication-0.0.1-SNAPSHOT.jar`

The application will be up at `http://localhost:8080`
