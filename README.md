## Assignment in Advanced Systems Integration & Architecture
1. Define Service Oriented Architecture(SOA)
-Service-oriented architecture (SOA) is an enterprise-wide approach to software development that makes use of reusable software components, or services. there’s a good chance someone will tell you that SOA was a failed idea. But you should challenge that line of thinking. If you revisit the actual principles of SOA, you will see they are as relevant today as they were when they were first constructed
2. List and discuss the characteristics of SOA.
-there multiple characteristics lest start with standardized service contracts in short it us used to transmit data with a set of resources and verbs in order to help consumer to use the service who want a hard to use API right another point is it allows service consumers to access to some specifications
-Loose Coupling - equal agility coupling is like combining two together some examples here are instead of connecting a person directly to the system why not put a service between that separate the two-system breaking the dependency 
-Abstraction – it breaks dependencies and introduces agility it also allows enterprise to define technology in the context in order to avoid unnecessary service information
-Service Reusability - form its word reusability like on a simple code instead of making a new why not iteration like loop or something also its cheap you can reduce development time and the associated support costs
Autonomy – it has independence or freedom like service should have control over the logic they encapsulate while service should be able to work alone or stand alone it should be watched for performance and usability in order to boost reliability and behavioral predictability 
-Statelessness – service treats each message it receives as independent transaction that not connect to the first request if a client asks for data the service responds but does not keep track or store any data it also increases service scalability it can provide multiple service one by one 
-Discoverability - it talks about metadata it’s a data about data Metadata is defined as the data providing information about one or more aspects of the data for discovery which also communicates purpose and capabilities to human the system must be educate the consumer on the proper way of mechanism to interact with certain service to accelerate its use
-Composability – in short, the big problems breaking it in to smaller pieces that easy to manage and start building there Enable your organization to combine packaged business capabilities to define business processes 
-Interoperability - the ability of computer systems or software to share and use data. Instead to making a new why not share it to another data if they have the similar software 
3. Define Microservices.
-an organizational and architectural method of developing software in which the program is made up of discrete, independent services that connect with each other using clear APIs. Its like SOA it made up of loosely coupled reusable and specialized components. However, rather than being adopted enterprise-wide, microservices are typically used to build individual applications in a way that makes them more agile, scalable, and resilient.

4. List and discuss the benefits of using Microservices.
-Independently deployable – form its characteristics microservices is that because the service is smaller and independently and its easy to fits model because of its size lastly it makes easier for new team members to understand it 
-Right tool for the job – it supports the entire application because it shares a common stack so it must share a common stack data or model and database
-Precise scaling – because it small it has its individual service it easy to individually deployed it require less infrastructure because enable precise scaling of the components instead of the entire app u can choose that what is only require it  

5. List and discuss the similarities and differences of SOA and Microservices.
-Independently deployable – form its characteristics microservices is that because the service is smaller and independently and its easy to fits model because of its size lastly it makes easier for new team members to understand it 
-Right tool for the job – it supports the entire application because it shares a common stack so it must share a common stack data or model and database
-Precise scaling – because it small it has its individual service it easy to individually deployed it require less infrastructure because enable precise scaling of the components instead of the entire app u can choose that what is only require it  
List and discuss the similarities and differences of SOA and microservices 
Reuse – in SOA it’s the primary goal and at an enterprise level on the other hand microservices is creating a microservices components that is reused
-Synchronous calls – its given here that SOA are available across the enterprise on the other hand microservice synchronous calls are real time dependencies 
-Data duplication – the aim of SOA is to provide service for all applications so instead of making new its primary sources which reduces the need to maintain on the other hand microservices ideally has local access to all data it needs this duplications ad’s complexity so it must be balanced 
-Communication – at microservices each service is developed independently on the other hand SOA share common communications 
Interoperability – just remember microservices use lightweight messages but SOA are open to heterogeneous diverse in character or content. messages 
Service granularity – microservices are used highly specialized services SOA on the other hand can range small to enterprise-wide services 
Speed – SOA focus on troubleshooting to improve slowly microservices which minimize sharing favor of duplication


(Park, 8 Principles of Service-Oriented Architecture: Is SOA Dead? , October 10, 2022) https://blogs.mulesoft.com/digital-transformation/soa-principles/
