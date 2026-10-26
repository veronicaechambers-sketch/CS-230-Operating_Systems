# CS 230 – The Gaming Room Software Design Portfolio

## About the Project

This portfolio artifact documents my work for CS 230: Operating Systems. The client for the project was **The Gaming Room**, which wanted to expand its existing Android game, **Draw It or Lose It**, into a web-based application that could support multiple computing platforms. The game is team-based and requires the application to manage games, teams, and players while maintaining unique names and identifiers. The project also required consideration of operating platforms, memory and storage management, distributed systems, networking, authentication, authorization, and security.

## Reflection

### 1. What was the client and what software did they want?

The Gaming Room was the client, and they wanted to expand Draw It or Lose It beyond its original Android-only environment. The goal was to design a web-based, distributed application that could communicate with desktop and mobile clients. The application needed to manage games, teams, and players, enforce unique names and identifiers, and provide a foundation that could scale as the number of players increased.

### 2. What did I do particularly well?

I think I did particularly well at organizing the technical requirements into a design that could be understood by both technical and nontechnical audiences. I used the software design document to connect the client's requirements to specific design decisions, including the Entity class, GameService, the Singleton pattern, and iterator-based searches for duplicate names. I also did well at evaluating multiple operating platforms and developing recommendations for Linux, storage, memory management, distributed networking, and security.

One of the areas I am especially proud of was connecting the design documentation to the working Java prototype. Completing the GameAuth portion also gave me practical experience with REST APIs, authentication, authorization, and role-based access.

### 3. What was helpful about working through the design document?

Working through the design document before and alongside the code helped me understand what the application was supposed to accomplish before focusing on individual programming tasks. The document gave me a place to identify requirements, constraints, relationships, and design patterns before implementing them.

For example, documenting the relationship between Game, Team, and Player helped me understand how the objects needed to work together. The design also helped me recognize why a shared GameService and unique identifiers were important. Later, when working with REST and security, the earlier architectural decisions made it easier to understand how the server, API endpoints, authentication, and authorization fit together.

### 4. If I could revise one part, what would I change?

If I could revise one part of my work, I would improve the architecture diagrams and expand them to show more of the complete distributed environment. The early design focused heavily on the application objects and relationships, while later work introduced additional concerns such as the web server, database, object storage, client devices, networking, authentication, and security.

I would create a more detailed architecture diagram showing how desktop and mobile clients communicate with the web application, how the application communicates with the database and image storage, and where security controls are applied. This would make the relationship between the different system components easier to understand at a glance.

### 5. How did I interpret and implement the user's needs?

I started with the client's actual requirements rather than choosing technology first. The Gaming Room needed a game that could support multiple teams and players, prevent duplicate names, maintain unique identifiers, and eventually operate across multiple platforms. I translated those needs into the object-oriented design and then extended the design into a client-server architecture.

Considering the user's needs is important because software can technically function while still failing to solve the customer's actual problem. A design that ignores usability, scalability, security, or the environments in which the software will be used can create expensive problems later. In this project, the need to support multiple platforms influenced the decision to separate the server-side business logic from the client presentation.

### 6. How did I approach designing software, and what will I do in the future?

My approach was to break the problem into smaller requirements and then connect those requirements to the architecture, objects, design patterns, and implementation. I looked at the relationships between Game, Team, and Player, considered the responsibilities of the GameService, and used patterns such as Singleton and Iterator where they supported the requirements. I then expanded the design to consider operating systems, memory, storage, networking, authentication, authorization, and security.

In the future, I would continue using a requirements-first approach. I would identify the users and their goals, document functional and technical requirements, identify constraints, create a high-level architecture, develop the domain model, select appropriate design patterns, and then build and test the application incrementally. I would also plan for security, scalability, accessibility, error handling, and maintainability early rather than treating them as additions after the application has been developed.

## Portfolio Artifact

The completed **CS 230 Software Design Document** is included in this repository. It demonstrates my ability to analyze a software problem, develop an object-oriented design, evaluate operating platforms, and recommend an architecture for a distributed application.

**Artifact:** `CS230_Project_Three_Software_Design_Document_Veronica_Chambers_FINAL.docx`
