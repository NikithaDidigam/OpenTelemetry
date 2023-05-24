# Distributed Tracing in Microservices using OpenTelemetry and Jaeger

## What is Opentelemetry
https://opentelemetry.io/docs/

## Step to set up this project
- mvn clean build each individual microservices 
- Run the docker-compose to spin up all microservices, Sleuth and Jaeger services

## Test the below endpoints
GET
http://localhost:8080/users/3229/generateReport

GET
http://localhost:8082/product/100003

## Jaeger URL
http://localhost:16686/

## ToDo:
* Implement Prometheus