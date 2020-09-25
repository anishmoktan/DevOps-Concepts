# DevOps-Concepts
DevOps terms and concepts

## Software Delivery Cycle
- Software delivery cycle is a best-practice methodology that defines the appropriate steps to follow when building efficient software. The cycle begins with brainstorming what problems the software is trying to solve, analyzing what components are required in order to achieve such goals, designing the architecture of the software, and developing to make the software come to life. The cycle then leads to deploying and testing the software, which allows us to see if the goals of the project were met. Finally the cycle encourages to maintain the software to make sure it stays running until bugs or new additional features are considered, which would ignite the cycle to start again.

## Test Driven Development
- TDD is a software development approach where test cases are developed to validate what the code of various features in a software will do. It is a micro approach of conducting various tests for the software's functionality and features to ensure the codes that build up to the overall software are working and deployable. This method allows developers to find and fix bugs effectively and faster to ensure smooth progression of the development of the software.  

## Continuous Integration
- Continuous integration is the practice of constantly merging code of a project in a shared repository, where automated builds and tests are run. It is part of the build and integration stage of the software delivery cycle and the core goals are to find bugs earlier, reduce the length of release updates, and improve the overall quality of the software. CI allows multiple developers to work together by preventing merge conflicts and implementing tests of the branch they’re working with to integrate the right code to the central repository. Overall, the practice improves developers’ productivity, helps them find and address bugs quicker, and deliver updates of the software faster. 

## Continuous Delivery
- Continuous delivery is a practice that expands upon continuous integration, where it focuses on automating the code changes that are prepared for a release to production. The goal is to continue automating beyond unit tests to mitigate bugs, verify updates across different features of the code, and to have deployment-ready software that passes through the testing process. Ultimately, continuous delivery lets teams of developers automatically build, test, and prepare code changes for release to production so that your software delivery is more efficient and rapid.

## Configuration Management

## Containerization
- Containerization is an effective technique that uses containers to deploy applications on the cloud. It allows us to keep the applications isolated to promote portability, agility, scalability/high availability, and optimization of revenue. Container are commonly used for continuous integration/continuous development automation, autoscaling microservices architectures, containers as service, and hybrid cloud architectures. Using containers allows us to better utilize the recourses on servers for easy, reliable, and accessible deployments of applications.

## Cloud Scalability, and Reliability
- Cloud Scalability means to be able to increase the compute power of a computer in the cloud on demand. For example, if a website usually hosts few hundreds of visitors on a daily basis and the website gains millions of visitos one night, the server would not be able to handle the volume and go out of service. Hence, cloud scalability is the method of giving the host the leverage to increase (scale) the computing power to meet the power required to host the website on demand. Reliability means as the servers are on the cloud, they are distributed to multiple nodes to ensure the server is safe and secured from hacks and data breaches. It would be up to the hosts to set their cloud servers in a way that they are able to withstand potential threats.  

## Software Architecture / Software Architecture Patterns
- the blueprint or the glue of a project that that must be followed out by design and implementation teams to understand how the end product should behave. Before begining a new project, an architecture must be rendered in order to understnad the goals, the frameowork, the components, and system qualities to unify a vision. An effective architecuure helps ignite an organized process that keeps the goals aligned and identify the risks which can be mitigated in different stages of the project. 
- Software architectural pattern are general, reusable solutions to a commonly occurring problem in software architecture within a given context.

## Client/Server 
- There are models that distribute the dividing tasks between servers and clients, which either reside in the same system or communicate through a computer network (internet). The client sends requests to another program in order to access a service made available by a server and the server runs one or more programs that share resources with and distribute work among clients. They communicate in request-response pattern and must follow the formal rules, languags, and dialog patterns (protocols). 

## Peer-to-Peer
- decentralized network on the internet where peers (computers) are connected to each other so files are shared directly between systems without the need of a central server. In other words, each computer on a P2P network becomes a file server as well as a client. Once connected, you can search for designated sharable files on other people's computer and others can do the same to your computer, causing unsecured transactions. P2P leads to piracy and illegal sharing of softwares and data.

## Monolithic 
- 

## Microservices 
- are the way of creating softwares where applications are broken down into smaller independent services and are not dependent upon a specific coding language. Development teams are able to use the language tools they are most comfortable with and achieve synergy in the application development process. Large complex applications can be divided into smaller building blocks and when recomposed, offer all of the functionality of a large scale, highly complex application. All of the microservices communicate with each other using HTTP requests on REST API. Benefits include the use of containers, APIs, and scabality on the cloud.

## REST
