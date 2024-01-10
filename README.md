# Spring Cloud Overview
## 1. Spring cloud Azure, Spring Cloud Alibaba, Spring Cloud AWS 
`TODO`
## 2. Spring Cloud Bus
##### Motivation:
- Distributed systems meet the communicate challenge that all services can communicate effectively
##### Solution:
- Spring Cloud Bus links all of the distributed system to do somethings like broadcast state changes (configuration), or communication bw services
##### Why:
- SCB is an event bus by leveraging RabbitMQ and Kafka for communication, that can broadcast events across all connected services as needed
##### How does it work ?
- SCB utilizes  Spring Cloud Stream (framework for bulding highly scalable), instance of a services pushs an event to SCB, it's brodcasted to all services connected to the bus and Spring can easy to get that information.
##### Around
- Use Spring Cloud Bus and Server Configuration to make the realtime changing configuration without restart the application

Explain: The Advanced Message Queuing Protocol (AMQP) is an open standard application layer protocol for message-oriented middleware
