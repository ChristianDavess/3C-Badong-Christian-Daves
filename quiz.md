## Long Quiz in Advanced Systems Integration & Architecture
1. Define Service Oriented Architecture (SOA)
    SOA is an enterprise-wide approach to software development that takes advantage of reusable software componets, or services.
2. List and discuss the characteristics of SOA
    1. Standardized Service Contracts - Services adhere to a service description
    2. Loose Coupling - Services minimize dependencies on each other and create specific types of relationships within and outside of service boundaries with a constant emphasis on reducing loosening dependendies between service contract, service implementation, and service consumers.
    3. Abstraction - Services hide the logic they encapsulated from the outside world.
    4. Service Reusability - Logic is divided into services with the intent of maximizing reuse.
    5. Autonomy - Services should have control over the logic they encapsulated.
    6. Stalelessness - Incorporate state management deferral extensions within a service design goal.
    7. Discoverability - Services can be discovered easily.
    8. Composability - Service execution should be efficient in that individual processing should be highly tuned.
    9. Interoperability - Services should use standards that allow divers subscribers to use the service.
3. Define Microservices
    Microservices is made up of loosely coupled, reusable, and specialized components. Microservices uses a cloud-native architectural approach and is typically used to build individual applications in a way that makes them more agile, scalable, and resilient.
4. List and discuss the benefits of using Microservices
    1. Independently deployable - Microservices enables an organization to create small, cross-functional teams around one service or a collection of services and have them operate in an agile fashion.
    2. Right tool for the job - Components are deployed independently and communicate over some combination of event streaming, and message brokers so its possible for the stack of every individual service to be optimized for that service.
    3. Pricise scaling - Individual services can be individually deployed but they can be individually scaled as well.
5. List and discuss the similarities and differences of SOA and Microservices
    Similarities
        1. Reusability - Both SOA and microservices promote the reuse of software components or services.
        2. Loose coupling - Both architectures aim to minimize dependencies between components, allowing for independent development and deployment.
        3. Service-oriented - Both SOA and microservices focus on organizing software around services that perform specific business functions.
        4. Interoperability - Both architectures utilize standardized protocols and standards for communication between services or components.
    Differences
        1. Scope - SOA has an enterprise-wide scope, focusing on standardizing integration across an organization, while microservices have an application scope, focusing on building individual applications.
        2. Communication - In microservices, each service is developed independently with its own communication protocol, while SOA services share a common communication mechanism called an enterprise service bus (ESB).
        3. Service granularity - Microservices are highly specialized and designed to do one thing well, while SOA services can range from small, specialized services to enterprise-wide services.
        4. Speed - Microservices architectures prioritize agility and performance by minimizing sharing and favoring duplication, while SOA architectures simplify development and troubleshooting but may operate more slowly.
        5. Data duplication - SOA aims to synchronize data across applications, reducing the need for complex data synchronization patterns, while microservices may accept data duplication to improve decoupling and resilience.
6. Define Web Services
    web Services are software systems designed to support interoperable machine-to-machine interaction over a network.
7. List and discuss the benefits of using Web Services
    1. Exposing the Existing Function on the network - Web services allow exposing the functionality of existing code over the network.
    2. Interoperability - Web services allow various application to talk to each other and share data and services among themselves.
    3. Standardized Protocol - Web services use standardized industry-standard protocol for communication.
    4. Low Cost Communication - Web services use SOAP over HTTP protocol, so you can use existing low-cost internet for implementing web services.
8. List and discuss the characteristics of Web Services
    1. XML-Based - Web services use XML at data representation and data transportation layers.
    2. Loosely Coupled - A consumer of a web service is not tied to that web service directly.
    3. Coarse-Grained - Businesses and interfaces that Java expose should be coarse-grained.
    4. Ability to be Synchronous or Asynchronous - In synchronous invocations, the client blocks and waits for the service to complete its operation before continuing. Asynchronous operations allow a client to invoke a service and then execute other functions.
    5. Supports Remote Procedure Calls (RPCs) - Web services allow clients to invoke procedures, functions, and methods on remote objects using an XML-based protocol.
    6. Supports Document Exchange - Web services support the transparent exchange of documents to facilitate business integration.
9. List and discuss the distinct roles in Web Services Architecture
    1. Provider - The provider creates the web service and makes it available to client applications who want to use it.
    2. Requestor - A requestor is the client application that needs to contact a web service. The client application can be a .Net, Java, or any other language-based application which looks for some sort of functionality via a web service.
    3. Broker - The broker is the application which provides access to the UDDI. The UDDI enables the client application to locate the web service.
10. List and discuss the Web Services Components
    1. SOAP (Simple Object Access Protocol) - An XML-based protocol for exchanging information between computers.
    2. WSDL (Web Services Description Language) - An XML-based language for describing the functionality offered by a web service.
    3. UDDI (Universal Description, Discovery, and Integration) - A platform-independent, XML-based registry for businesses to lost their web services and for client to discover them.
