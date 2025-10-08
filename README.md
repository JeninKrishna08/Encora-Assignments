# Encora-Assignment
E-Commerce Microservices Project (Spring Boot & Apache Kafka)
This project is a simple e-commerce application built using Spring Boot, Maven, and Apache Kafka.  
It shows how different services can work together in a microservices architecture to manage orders.

## Microservices

### Amazon Service
- Creates orders using a REST API.  
- Sends order details to a Kafka topic.

### Flipkart Service
- Listens to the Kafka topic.  
- Shows the received orders using a REST API.

## Main Features
- REST APIs for creating and viewing orders.  
- Uses Kafka for communication between services.  
- Follows producer-consumer microservice design.  
- Built with a Maven multi-module structure.  
- Easy to add more services later.

## Technologies Used
- Java 21  
- Spring Boot 3.3.3  
- Apache Kafka  
- Maven  
- REST APIs  

## How to Run

1. Start Kafka broker.  
   Make sure ZooKeeper and Kafka are running on your system.

2. Run both applications:  
   - AmazonApplication  
   - FlipkartApplication  

3. Test the services:  
   - POST /orders/create - to create a new order  
   - GET /api/orders/received - to view received orders      



  
