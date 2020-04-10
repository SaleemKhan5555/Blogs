# Blogs
Microservices Architecture
What are Micros Services
In software development domain, microservices is a new architectural approach in which a single application is composed of many small independent modules or services modeled around a business domain. In this approach each independent module or services is self-contained and implements a single business capability. It makes application easier to build, much easier to expand and scale.
Monoliths : A Traditional Approach 
Monolith approach is a traditional way of building enterprise applications which has become more complex as application gets expand. A monolithic application is built as a single unit contains all the code for all business activities an application performed. Enterprise Applications are built in three parts: a database (consisting of many tables usually in a relational database management system), a client-side user interface (consisting of HTML pages and/or JavaScript running in a browser), and a server-side application. This server-side application will handle HTTP requests, execute some domain-specific logic, retrieve and update data from the database, and populate the HTML views to be sent to the browser. It is a monolith – a single logical executable. In a monolith, server side application logic, front end , client side logic, background jobs, etc, are all defined in the same massive code base. To make any modifications to the system developer will build and deploy the entire stack all at once.
Differences Between Traditional Architecture and Microservices Architecture
In monolithic approach enterprise application is build as a single unit that contains all code. While in microservice architecture , applications are build into multiple independent modules that works together seamlessly. These modules are individually responsible for performing precisely defined, standalone tasks and communicate with each other through simple, universally accessible application programming interfaces (APIs). In order to understand the difference between monolithic and microservices approach, consider an E-commerce application as shown in figure below.

Key Advantages of Micro Services
1)	Independent Development – All microservices can be easily developed based on their individual functionality
2)	Independent Deployment – Based on their services, they can be individually deployed in any application 
3)	Fault Isolation – Even if one service of the application does not work, the system still continues to function
4)	Mixed Technology Stack – Different languages and technologies can be used to build different services of the same application
5)	Granular Scaling –  Individual components can scale as per need, there is no need to scale all components together
6)	Increased developer productivity - New developers can get up to speed rapidly, since it’s easier to understand a small, isolated piece of functionality than an entire monolithic application.
7)	Better alignment of developers with business users. Since microservice architectures are organized around business capabilities, developers can more easily understand the user perspective and create microservices that are better aligned with the business. 
8)	Future-proofed applications- When innovations happen and new or updated technology disrupt your software development process, microservice architectures makes it easier to respond by replacing or upgrading the individual services affected without impacting the whole application.
