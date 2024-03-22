# Be a 10x Enginner

This documents compiles all the knowlede I have accumalted over last 7 years in my experience. I still believe there is lot to be done.
This is my attemt to explain in a simple and easy way. There are thing which even I do not undestand fully.
Sole pupose here is to share what I know and in the process learn from you what I do not know.

There is a popular saying 

> _" khushi baatne se badhti hai, dukh baatne se kam hote hai " (happiness increases & sadness reduces on sharing with others)_

As a Software Engineer , what I believe

> _" knowledge baatne se badhti hai, doubts baatne se kam hote hai " (knowledge increases & doubts reduces on sharing with others)_ 

Please feel free to point or any mistake you find out or any feedback you have for me. We can work together. Raise a PR or reach
out to me on nitishlvashisth@gmail.com or via [Linkdin]([url](https://www.linkedin.com/in/nitish-vashisth-31858366/))

# Topic that need to be prepared well for Interviews

  -  [Programming Language](#programming-language)
  -  [Java](#java)
  -  [DSA and Algorithm](#dsa-and-algorithm)
  -  [Low Level System Design Low(LLD](#low-level-system-design-lowlld)
  -  [High Level System Design (HLD)](#high-level-system-design-lld)
  -  [Software Architecture Pattern](#software-architecture-pattern)
  -  [System Design Questions](#system-design-questions)
  -  [Microservice Design Patterns](#microservice-design-patterns)
  -  [Maven](#maven)
  -  [SpringBoot](#spring-boot)
  -  [Rest Web Service](#rest-web-service)
  -  [Cloud](#cloud)
  -  [DevOps](#devops)
    	* Docker
     	* Kuberneetes 
  -  [Past Companies / Projects](#past-companies--projects)
  -  [Other Topics](#other-topics)
    


## Programming Language
Choosing a programming language and try to deep dive into it. Below are some of the programming langauga one can choose from
* Java
* Python
* C/C++
* C#

I'm an expert in Java and have understanding of python. If you have queries or doubt around it reach out to me.

## Java
* Core Java
* Java 8 - 17

## DSA and Algorithm
1 Asymptotic Notations
1.1.1	Time Complexity
1.1.2	Space Complexity

## Low Level System Design Low(LLD)

### OOPs Concepts
* Class, object,  Abstract Class, Interface
* Pillars of OOPs
  *Abstraction
  *Encapsulation
  *Inheritance
  *Polymorphism

### Coupling / Cohesion

### SOLID Principles
Benefits
* Helps us to write better code.
* Avoid duplicate code.
* Easy to maintain.
* Easy to understand.
* Flexible Software
* Reduce complexity.

**S** -> Single Responsibility 
	The Single Responsibility Principle states that a class should have only one reason to change, meaning it should have only one job or responsibility. This promotes code modularity and makes it easier to maintain and extend the codebase.

**O** -> Open / Close
	The Open-Closed Principle emphasizes that a class should be open for extension but closed for modification. This means that you should be able to add new functionality to a class without altering its existing code

**L** ->  Liskov’s Substitution
The Liskov Substitution Principle emphasizes that objects of a superclass should be replaceable with objects of its subclasses without affecting the correctness of the program. This means that the behaviour of a subclass should not contradict the behaviour of its superclass.

**I**   -> Interface segregation
The Interface Segregation Principle states that a client should not be forced to implement interfaces it doesn’t use. This promotes smaller, specific interfaces rather than large, monolithic ones.

**D** -> Dependency Inversion
	The Dependency Inversion Principle advocates that high-level modules should not depend on low-level modules. Both should depend on abstractions. This promotes decoupling and flexibility in your code.

Or 

class should depend on interface rather than concrete class.


### Other Principles
* DRY (Don't repeat yourself)
* Encapsulate What Changes
* Favor Composition over Inheritance
* Programming for Interface not implementation
* Delegation principles

### Design Patterns
| Creational       | Structural  | Behavioural  |
| ---------------- | ----------- | ------------ |
| Abstract Factory |  Adapter    |   Chain of Responsibility  |
| Factory          |    Bridge   |   Command  |
| Singleton        |  Composite  |  Iterator   |
| Builder          |  Decorator  |    Mediator |
| Prototype        |     Facade  |   Memento  |
|                  |  Flyweight  |   Observer  |
|                  |     Proxy   |   State  |
|                  |             |   Strategy  |
|                  |             |   Template Method  |
|                  |             |   Visitor  |

## High Level System Design (LLD)
I have created a seperate reposioty for this. Please refer from here
[System-Design-Champion](https://github.com/nitish131992/System-Design-Champion)

It coveres following topic :
* What is System Design
* CPU and Memory
* Horizontal and vertical scaling
* Hard Drive / Network Bandwidth
* CAP Theorem
* Load Balancer
* Asyncronous Processing Queue
* Cloud (AWS, Azure, GCP)
* Deployment
* DNS
* HTTP vs HTTPS
* CDN and Edge
* Cahcing
* Misc Topics
* Consistent Hashing
* Database
* Node Replication Startegy
* Search
 
## Software Architecture Pattern
* Layered Pattern
* Event Driven	
* Client Server 
* Microkernel
* Microservices
* Monolithic

## System Design Questions
| S.No | LLD  | HLD  |
| ------- | --- | --- |
| 1 | LRU Cache         | Book My Show       |
| 2 | ATM Design        | Tiny Url           |
| 3 | Vending Machine   | Make My Trip       |
| 4 | Elevator Design   | [Uber System Design](https://techbacklog.com/uber-system-design) |
| 5 | Parking Lot       | Ecommerce System (Amazon)   |
| 6 | Hashmap Internals | Whatsaap           |

## Microservice Design Patterns

| Decomposition            | Integration                | Data Pattern                       | Observability               |
| ----------------------   | -------------------------- | ---------------------------------- | --------------------------  |
| Business Process Based   | Gateway Pattern            | Single Service Databse             | Log Aggragation Pattern     |
| Domain Based             | Process aggregator pattern | Shared Service Database            | Metrics Aggrgation          |
| Atomic transaction based | Edge Pattern               | Asyncronous Eventing               | Tracing Pattern             |
| Strangler Pattern        |                            | CQRS                               | Extrenalized Configuration  |
| Sidecar Pattern          |                            | SAGA (Coreography & Orchsetartion) | Health Check                | 
|                          |                            |                                    | Service Discovery           |     

* Cross Cutting Concerns

![image](https://github.com/nitish131992/Interview-Backend/assets/19357644/a8445523-c1b0-4f35-836a-3754ebcc9cb6)


## Maven

## Spring Boot

## Rest Web Service 

## Cloud
* AWS
* Azure
* GCP
* Blue Ocean

## Devops
* Docker

How does Docker work?

The diagram below shows the architecture of Docker and how it works when we run “docker build”, “docker pull” and “docker run”.

There are 3 components in Docker architecture:

🔹 Docker client
The docker client talks to the Docker daemon.

🔹 Docker host
The Docker daemon listens for Docker API requests and manages Docker objects such as images, containers, networks, and volumes.

🔹 Docker registry
A Docker registry stores Docker images. Docker Hub is a public registry that anyone can use.

Let’s take the “docker run” command as an example.
1. Docker pulls the image from the registry.
2. Docker creates a new container.
3. Docker allocates a read-write filesystem to the container.
4. Docker creates a network interface to connect the container to the default network.
5. Docker starts the container.


  ![Docker](https://github.com/nitish131992/Interview-Backend/assets/19357644/7500dc73-f29d-4927-b0e3-860ca868df73)

* Kubernetes

## MicroService Design Pattern
     

* Dashboar and Alerts setup. Ensure to hava a run book for all alerts

## Past Companies / Projects

# Other Topics

  
