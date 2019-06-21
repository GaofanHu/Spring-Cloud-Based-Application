# Spring-Cloud-Based-Application

This is an individual project based on Spring Cloud microservice architecture. 

I developed advertisement aggregating microservice and searching microservice based on spring cloud for accurate advertising. 

The aggregating microservice is used to collect advertisement information from advertiser. The searching microservice is used to search corresponding advertisement from database based on keywords, location and other limits.

Run application:

Firstly, start MySQL server and Kafka. Then, start main functions of Eureka application and Zuul gateway application. After that, start main function of ad-sponsor to run aggregating microservice and start main function of ad-search to run searching microservice.
