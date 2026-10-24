# CS-230 Operating Platforms

## Project Overview

This repository contains my completed Software Design Document for CS-230 Operating Platforms at Southern New Hampshire University.

The project involved working as a technology consultant for The Gaming Room, a fictional client seeking to expand its Android-based game, *Draw It or Lose It*, into a web-based application accessible across multiple operating systems.

The application needed to support multiple games, teams, and players while maintaining unique identifiers, preventing duplicate names, and providing a consistent experience across desktop and mobile devices.

The project included developing a Java application using object-oriented programming principles and design patterns, evaluating different operating platforms, and recommending an architecture capable of supporting a distributed web application.

## Technologies and Concepts

- **Java:** Object-oriented application development
- **Design Patterns:** Singleton and Iterator
- **Operating Systems:** Linux, Windows, macOS, Android, and iOS
- **Server Architecture:** Client-server and distributed systems
- **Storage Management:** Linux ext4 and PostgreSQL
- **Memory Management:** Virtual memory, paging, and Java garbage collection
- **Networking:** HTTPS, REST APIs, and WebSockets
- **Security:** Authentication, authorization, access controls, and encryption

## Project Reflection

### Briefly summarize The Gaming Room client and their software requirements. Who was the client? What type of software did they want you to design?

The Gaming Room was a client looking to expand its existing Android game, *Draw It or Lose It*, into a web-based application accessible across multiple operating systems. The application needed to support multiple games, teams, and players while ensuring unique identifiers and preventing duplicate names. The client also needed a scalable solution capable of supporting thousands of players across desktop and mobile devices.

### What did you do particularly well in developing this documentation?

I believe I did particularly well at organizing the technical requirements and explaining how the different components of the application work together. Rather than evaluating each operating system independently, I focused on how server infrastructure, client compatibility, storage, memory management, and networking contribute to the overall application. This helped me develop a consistent recommendation based on the client's requirements.

### What about the process of working through a design document did you find helpful when developing the code?

Working through the design document helped me understand the application's requirements before focusing on implementation. The UML class diagram was particularly useful because it showed the relationships between GameService, Game, Team, Player, and Entity. Having these relationships defined made it easier to understand how to organize the Java classes and apply design patterns such as Singleton and Iterator.

### If you could choose one part of your work on these documents to revise, what would you pick? How would you improve it?

I would expand the system architecture documentation to include a more detailed diagram showing how the browser clients, application servers, and database communicate. While the written recommendations explain the proposed distributed architecture, a visual representation would make it easier to understand the relationships between the components. I would also explore how active game sessions could be synchronized across multiple servers.

### How did you interpret the user's needs and implement them into your software design? Why is it so important to consider the user's needs when designing?

I began by identifying the client's business and technical requirements, including cross-platform accessibility, support for multiple players, and consistent game data. These requirements influenced the decision to recommend a Linux server with a browser-based interface, allowing users on different operating systems to access the same application. Considering user needs is important because technical decisions should support the application's intended functionality and provide a reliable experience rather than simply reflect the developer's preferred technologies.

### How did you approach designing software? What techniques or strategies would you use in the future to analyze and design a similar software application?

I approached the project by breaking down the requirements, identifying design constraints, developing the object-oriented structure, and evaluating the technologies needed to support the application. The UML diagram and design patterns helped establish the application's internal structure, while the operating platform evaluation helped guide the infrastructure recommendations. In future projects, I would continue using requirements analysis, UML diagrams, design patterns, and platform comparisons to evaluate potential solutions before implementation.

## Software Design Document

The completed Software Design Document includes the application's requirements, design constraints, UML domain model, operating platform evaluations, and architectural recommendations.

The document demonstrates the progression from initial software requirements to a proposed distributed system architecture.

## Software Design Document

[View Completed Software Design Document](CS230_Software_Design_Document.pdf)
