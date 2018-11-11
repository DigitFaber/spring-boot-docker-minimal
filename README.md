# Minimal Maven project for dockerized Spring Boot application.

##### To try the application, go to the desired folder and enter the following commands:
```sh
git clone https://github.com/DigitFaber/spring-boot-docker-minimal.git
cd spring-boot-docker-minimal
mvn package docker:build
docker-compose up -d
```
Then open this link in the web browser: [http://localhost:8080/](http://localhost:8080/)

##### To close the application, enter:
```sh
docker-compose down
```
