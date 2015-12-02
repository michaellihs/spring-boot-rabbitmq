Spring-Boot Demo Application
============================

## How to build the project

Run `mvn clean install` and `mvn package`. This results in a `target/WHATEVER.jar` file

## How to run the application

Run `java -jar target/WHATER.jar`

## How to access the application

Go to your browser and open [http://localhost:8080/hello/world](http://localhost:8080/hello/world)

## How to install the RabbitMQ Server

Run `brew install rabbitmq` afterwards launch the server with `rabbitmq-server`

### How to access the RabbitMQ UI

Open [http://localhost:15672/](http://localhost:15672/) in your browser. Username is `guest` password `guest`.
