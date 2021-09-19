# Reading Task 2: SOA
A reading assignment on Service Oriented Architecture.

1. On up to two pages, give an answer to the following questions, in text and diagrams, as appropriate:
* <b>What is SOA?</b>
<br>Service-Oriented Architecture is an approach to software development architecture. It outlines how to make software components reusable using interfaces. The applications of SOA make use of services available in the network.
* <b>Which are the main building blocks of SOA architecture?</b>
<br>"There are three roles in each of the Service-Oriented Architecture building blocks: service provider; service broker, service registry, service repository; and service requester/consumer."
<br>According to [the approved source used for SI lesson preparation week 38](https://medium.com/@SoftwareDevelopmentCommunity/what-is-service-oriented-architecture-fa894d11a7ec).
* <b>What are the advantages of applying it in enterprise applications development?</b>
<br>"Advantages of SOA: 
    * Service reusability:
    <br>In SOA, applications are made from existing services. Thus, services can be reused to make many applications.
    * Easy maintenance: 
    <br>As services are independent of each other they can be updated and modified easily without affecting other services.
    * Platform independent: 
    <br>SOA allows making a complex application by combining services picked from different sources, independent of the platform.
    * Availability: 
    <br>SOA facilities are easily available to anyone on request.
    * Reliability: 
    <br>SOA applications are more reliable because it is easy to debug small services rather than huge codes
    * Scalability: 
    <br>Services can run on different servers within an environment, this increases scalability"
<br>According to GeeksforGeeks's [article on SOA](https://www.geeksforgeeks.org/service-oriented-architecture/).

* <b>What are the disadvantages of applying it in enterprise applications development?</b>
<br>"Disadvantages of SOA:
    * High overhead: 
    <br>A validation of input parameters of services is done whenever services interact this decreases performance as it increases load and response time.
    * High investment: 
    <br>A huge initial investment is required for SOA.
    * Complex service management: 
    <br>When services interact they exchange messages to tasks. the number of messages may go in millions. It becomes a cumbersome task to handle a large number of messages."
<br>Also according to GeeksforGeeks's [article on SOA](https://www.geeksforgeeks.org/service-oriented-architecture/).

* <b>Which basic principles should the developers of SOA consider?</b>
<br>"A service has four properties according to one of many definitions of SOA:[3]

    It logically represents a repeatable business activity with a specified outcome.
    It is self-contained.
    It is a black box for its consumers, meaning the consumer does not have to be aware of the service's inner workings.
    It may be composed of other services.[4]" 
According to Wikipedia's [article on SOA](https://en.wikipedia.org/wiki/Service-oriented_architecture).

2. There exists a document, known as SOA Manifesto, which defines six values of priority in the work of the developers of SOA. Write those values in your own priority order (these you find most important should be at the top of the list) and explain your arguments.

The original order:
* Business value over technical strategy.
* Strategic goals over project-specific benefits.
* Intrinsic interoperability over custom integration.
* Shared services over specific-purpose implementations.
* Flexibility over optimization.
* Evolutionary refinement over pursuit of initial perfection.

My personal feeling is that this priority order very well demonstrates the priority list you'd likely find optimal for a business with many projects simultaneously and over time, which is why the strategic goals supercede the project-specific benefits - you would rather aim for the benefit of the whole company even if one project takes a hit.
<br>However a business able to fully focus on one project might lay out this priority order differently.
