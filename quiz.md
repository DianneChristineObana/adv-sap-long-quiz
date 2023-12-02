## Long Quiz in Advanced Systems Integration & Architecture
1. Define Service Oriented Architecture (SOA).
Answer: 
It is an application development or integration that makes software components reusable and able to exchange information to create new applications and communicate through services bus. SOA removes certain tasks from the application developer that previously redeveloped an existing functionality. Since SOA is an architectural approach it uses communication standards to advance service integrations in applications. It helps the developers to integrate the different services that they want to set to their new application by providing a common process that guides the user to use easily the diverse services in the application. 
2. List and discuss the characteristics of SOA.
Answer:
- Service Autonomy - is the encapsulation of the logic of a system because the user has no idea how the transaction works inside a system. Only the service provider holds the information since they control the logic they encapsulate.
- Service Discoverability - when we label or note a specific task the user will understand how a system will work, which is communicative metadata that can be interpreted or discovered easily.
- Standardized Service Contracts - when we set an agreement to an application we express the purpose why we need to follow a certain agreement. Considering that services adhere to have communication agreement defined collectively by one or more services.
- Loose Coupling - is when different services are needed for an application that can join or leave a couple or decouple. It minimizes the dependencies between the services and makes them explicit dependencies more lightweight
- Service Reusability - we reuse services so that we don't need to start from scratch when we want to make an application again. Since services are independent of their particular process, they can be composed or recomposed to the new layout.
- Abstraction -  it hides the logic of the services that they encapsulate from the outside of the application which makes them unaccessible from the users. It helps to avoid unnecessary service information which can be more confidential.
- Composability - is when we need to combine the different services that we put inside our application with other services.
- Statelessness - the services should be stateless which would be ideal since they should not retain information from one state from another state. It should be firmer to handle.
- Interoperability - the services need to use standards to allow diverse users to make them communicate through standard communication protocols.
3. Define Microservices.
Answer:
It is a split of applications into smaller applications and each part has its responsibility. The application is developed as a collection of services that can accommodate a feature and handle distinct tasks in an application.
4. List and discuss the benefits of using Microservices.
Answer:
Microservices are popular with executives and project leaders because they allow each service to become independent to meet the requirements from the application. Here are the three benefits of Microservices.
> Independently deployable - from the word itself it can deploy without depending on the other services since it enables the organization to create cross-functionality in the collection of services.
> Right tool for the job - since it is architecture patterns it is so easy and much less expensive for the smaller services to evolve their applications to more desirable technology.
> Precise scaling - the services can be deployed individually within their duration which becomes a benefit.
5. List and discuss the similarities and differences of SOA and Microservices.
Similarities:
* They can reuse, couple, and specialize the existing and non-existing components.
* Having multiple services that can interact with one another and the result will be one particular software application.
* They both allow the development teams to deploy, build, and manage.
* Both architectural methods.

Differences:
* SOA is a centrally governed architecture, while Microservices decentralized governing architecture.
* The architecture and the coordination because SOA contains four different types of services. On the other hand, microservices only have two types of services.
* The heterogeneous interoperability since SOA has messaging middleware that acts as a communication point between the different applications. While microservices do not have any broker in which the communication is directly between application to application.
* The service granularity of microservices is split into smaller parts while SOA is not broken down into smaller parts, it is a whole compacted service.
* Component Sharing of SOA has only one Order service unlikely to the microservices each task has its order service.
6. Define Web Services.
Answer:
Since in the previous question, I answer what is SOA and it tells that it is the implementation od the web services. Web services is the software service provider that publishes the service description which is placed in a certain directory. In the directory it contains the service  description that providers fill in and the consumer can create queries in opposition to the directory to find out what are the services available and how this services communicate with the provider.
7. List and discuss the benefits of using Web Services.
>> Exposing the Existing Function on the Network - using HTTP it can exposed your present code over the network which it can be available to use it other applications.
>> Interoperability - it gives authorization to numerous applications to communicate and share information to each other.
>> Standardized Protocol - it uses industry-standard protocol for communication which gives advantages in the web services protocol stack.
>> Low Cost Communication - for you to implement your web services in a low-cost internet, it uses the SOAP protocol to provide you a reliable services.
8. List and discuss the characteristics of Web Services.
>> XML-Based - it use to data representation and transportation of data layers which help to exclude any operating system.
>> Loosely Coupled - it is the connection of the client and server where if one of them changes something in the system it should keep the other one up to date.
>> Coarse-Grained - it uses the coarse-grained to have a broader scope to access the business-logic.
>> Ability to be Synchronous or Asynchronous - synchronous only send a one request to the server which blocks and wait for the service. Asynchronous is the who non-blocking that allows the client send a multiple request on the server.
>> Supports Remote Procedure Calls (RPCs) - allows client to call the methods on the remote objects using the XML-based protocol which can employ a request to the service from a program.
>> Supports Document Exchange - since it rely on XML, they cand send complex data or documentr without any problems. 
9. List and discuss the distinct roles in Web Services Architecture.
>> Provider - it is the host of the services or the one who creates a web service for client application.
>> Requestor - the one who initiate an interaction with a service.
>> Broker - is the one who allow the application to access to the UDDI which help the client to detect the web service. The broker also have the service provider, service requestor, and service registry.
10. List and discuss the Web Services Components.
>> SOAP - the envelope for request or response.
>> WSDL - this is the interface or the fucntionalities of the web services.
>> UDDI - the repository or the yellow pages of the web service.
