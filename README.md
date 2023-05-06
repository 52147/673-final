# 673-final 期末考猜題
## Sample Questions
1. Explain why microservices should have low coupling and high cohesion. 

- In microservices architecture, low coupling and high cohesion are essential characteristics.
- Low coupling means that services should be loosely connected, while high cohesion means that services should be highly focused.
- Having low coupling and high cohesion allows for greater flexibility, scalability, and ease of maintenance in microservices architecture.
2. You are a software product manager for a company developing educational software products based around scientific simulations to be used by colleges. Explain why it is important to develop a product roadmap so that final product releases are available in the first three months of the year. 

- Developing a product roadmap for first quarter releases is important for timeliness, competitive advantage, and revenue generation.
- A product roadmap can help ensure that product releases are planned and executed efficiently, taking into account development, testing, and deployment timelines.

3. In the context of RESTful services, explain what is meant by a ‘resource’. How do RESTful services address resources and operate on them? 

- In RESTful services, a resource is a unit of information that can be accessed and manipulated through a well-defined interface.
- RESTful services operate on resources using HTTP methods such as GET, POST, PUT, and DELETE.
- Examples of resources in an educational software product could include student records, course schedules, and quiz questions.
- HTTP methods allow clients to access and modify resources in a RESTful service.
## lecture 1
### Product Manager
- Product management is a complex discipline that requires multiple skills to master.
- A framework for effective product management consists of six core knowledge areas and six supporting ones.
- The six core areas are vision and leadership, product life cycle management, product strategy and market research, business model and financials, product roadmap, and user experience and product backlog.
- The supporting areas are general market knowledge, development/technologies, marketing, sales and support, project/release management, and process.
- Effective product management requires establishing a shared vision, setting realistic goals, managing stakeholders, actively listening, negotiating, and making tough product decisions.
- It also involves understanding the product life cycle, identifying target users and customers, segmenting the market, performing competitor analysis, and positioning the product.
- The financial aspect of product management involves understanding business goals, describing how the product's value proposition is monetized, creating a financial forecast or business case, and working with colleagues from the finance department.
- Creating a product roadmap requires formulating realistic product goals, metrics and key performance indicators, release dates or timeframes, and key features. It also involves formulating a go-to-market strategy and understanding when the roadmap should be reviewed and changed.
Delivering a great user experience involves describing the desired user experience, creating scenarios, epics, user stories, storyboards, workflow diagrams, and storymaps, prioritizing and managing the product backlog, and selecting sprint goals.
- The supporting knowledge areas involve understanding current customers and users, software technologies, marketing channels, sales channels, project/release management, and ideation and innovation processes.
- The framework can be used to define specific product roles and identify gaps in product knowledge, as well as to determine learning measures for individuals or groups of product managers or product owners.
### Devops
- DevOps is a set of practices and cultural values that promote collaboration and integration between development and operations teams.
- It involves breaking down traditional silos and fostering a shared sense of responsibility for delivering and maintaining a product or service.
- DevOps aims to automate software delivery and infrastructure management using tools like continuous integration and delivery, automated testing, and infrastructure as code.
- Observability is a critical component of DevOps, enabling teams to monitor and measure the performance and behavior of software and infrastructure in real-time.
- A DevOps culture values collaboration, transparency, continuous learning and improvement, and a willingness to experiment and take risks.
- DevOps requires a holistic approach to software and infrastructure development, with a focus on aligning business objectives with IT goals.
- Overall, DevOps is about improving the efficiency, quality, and reliability of software delivery and infrastructure management through a collaborative and continuous approach.
## lecture 2
### Agile
- Agile development is a widely adopted methodology in software development.
- However, many projects claiming to be Agile may not be truly Agile.
- Agile is a mindset for software development, not just a process or toolbox.
- People and interactions should be valued over processes and tools.
- Agile recognizes change as inevitable and provides meetings to manage it.
- Self-organizing teams are effective teams, and practices cannot be imposed on a team.
- Work should be done as late as possible, and success cannot be easily replicated in software development.
- Respect for people is important, and communication is key.
- The Agile mindset complements Agile processes and practices.
- Agile processes and practices should be seen as a toolbox to pick from as needed, not a rigid set of rules.
### Scrum
- Scrum is an Agile framework for managing and completing complex projects.
- It was originally developed for software development projects, but can be applied to any project where flexibility and adaptability are required.
- The framework consists of three main roles: the Product Owner, the Scrum Master, and the Development Team.
- The Product Owner is responsible for creating and maintaining the product backlog, a prioritized list of features or tasks that need to be completed.
- The Scrum Master is responsible for facilitating the Scrum process and ensuring that the team is following the framework.
- The Development Team is responsible for delivering a potentially releasable product increment at the end of each sprint.
- Sprints are fixed-length iterations of one to four weeks, during which the team works to complete a set of items from the product backlog.
- Each sprint begins with a sprint planning meeting, where the team plans what work they will complete during the sprint.
- Daily scrum meetings are held to provide updates on progress and identify any obstacles or issues that need to be addressed.
- At the end of each sprint, the team holds a sprint review to demonstrate the completed work to stakeholders and receive feedback.
- The sprint ends with a sprint retrospective, where the team reflects on the sprint and identifies areas for improvement.
- Scrum emphasizes self-organizing teams, with team members collaborating and taking ownership of their work.
- The framework is designed to be flexible and adaptable, with the team able to adjust their approach based on feedback and changing circumstances.
- Scrum can be combined with other Agile methodologies, such as Kanban or Extreme Programming (XP), to create a hybrid approach.
- To successfully implement Scrum, it is important to have buy-in from all team members and stakeholders, and to have a clear understanding of the framework and its principles.
### CI/CD
## lecture 3
### feature driven
- Feature-Driven Development (FDD) is an agile process designed to work for larger projects and teams.
- FDD was invented by Jeff De Luca and is often overlooked in the agile software development community.
- FDD uses "just enough" upfront activities to support additional communication needed in larger projects/teams.
- FDD organizes projects around five processes, the first three of which are equivalent to iteration zero activities.
- The first process involves creating a domain object model in collaboration with domain experts to establish a shared vocabulary.
- The second process involves building a features list, which is organized into a three-level hierarchy based on domain subject areas and business activities.
- The third process involves constructing an initial schedule, assigning responsibilities to Chief Programmers, and establishing individual class ownership.
- FDD does not use the term "iteration zero," but instead calls the initial processes "initial project-wide activities."
- FDD's upfront activities are not about big design upfront (BDUF), but about doing "Just Enough Design Initially" (JEDI).
- Experienced object modelers and development/project managers guide the modeling and planning teams in FDD.
https://dzone.com/articles/introduction-feature-driven
### persona
- A persona is a way to model, summarize, and communicate research about people who have been observed or researched in some way.
Each persona represents a significant portion of people in the real world and enables the designer to focus on a manageable and memorable cast of characters.
- A persona document should clearly communicate and summarize research data, but the document itself is not the most important thing. The fundamental understanding of users is what’s important.
- Alan Cooper informally developed personas in the early ’80s as a way to empathize with and internalize the mindset of people who would eventually use the software he was designing.
- Personas are an essential part of goal-directed design, which combines new and old methodologies from ethnography, market research, and strategic planning to simultaneously address business needs, technological requirements, and user goals.
- Personas are never used in isolation, but rather are implemented in conjunction with other processes, concepts, and methods that support and augment their use.
### user story
## lecture 4
### architectural style
#### client/server architectural style:

Client/server architecture involves a separate client and server system connected by a network.
The simplest form is a 2-Tier architecture, where a server application is accessed directly by multiple clients.
Historically, client/server architecture referred to a graphical desktop UI application that communicated with a database server or dedicated file server.
Today, examples of the client/server architectural style include web browser-based programs, Microsoft Windows operating system-based applications, and tools and utilities that manipulate remote systems.
Other variations on the client/server style include client-queue-client systems, peer-to-peer applications, and application servers.
Benefits of the client/server architectural style include higher security, centralized data access, and ease of maintenance.
The client/server architectural style is suitable for applications that are server-based and support many clients, web-based applications, business processes used by people throughout an organization, and services for other applications to consume.
The traditional 2-Tier client/server architectural style has several disadvantages, such as close combination of application data and business logic on the server and dependence on a central server.
To address these issues, the client/server architectural style has evolved into the more general 3-Tier (or N-Tier) architectural style, which provides additional benefits.
#### Client/Server:

Involves a separate client and server system with a connecting network
Client initiates one or more requests and waits for replies from the server
Examples include web-based programs, Microsoft Windows-based applications, and tools that manipulate remote systems
Benefits include higher security, centralized data access, and ease of maintenance
Disadvantages include closely combined application data and business logic, and dependence on a central server
#### N-Tier/3-Tier:

Segments functionality into tiers that can be located on physically separate computers
Each tier is independent of all other tiers except for those immediately above and below it
At least three separate logical parts, each responsible for specific functionality
Benefits include maintainability, scalability, flexibility, and availability
Consider using if processing requirements of layers differ, or security requirements of layers differ
Object-Oriented:

Based on the division of responsibilities into individual reusable and self-sufficient objects
Views a system as a series of cooperating objects instead of a set of routines or procedural instructions
Key principles include abstraction, composition, inheritance, encapsulation, polymorphism, and decoupling
Benefits include understandability, reusability, testability, extensibility, and high cohesion
Consider using if you want to model your application based on real world objects and actions, or you have complex business logic that requires abstraction and dynamic behavior
#### Service-Oriented:

Enables application functionality to be provided as a set of services, and the creation of applications that make use of software services
Services are loosely coupled and use standards-based interfaces that can be invoked, published, and discovered
Key principles include autonomy, distributability, loose coupling, shared schema and contract, and compatibility based on policy
Benefits include domain alignment, abstraction, discoverability, interoperability, and rationalization
Consider using if you have access to suitable services that you wish to reuse, want to build applications that compose a variety of services into a single UI, or are creating cloud-based applications.    


 https://learn.microsoft.com/en-us/previous-versions/msp-n-p/ee658117(v=pandp.10)
## lecture 5

## lecture 11
### software testing
software testing mentioned in the article:

#### Unit tests:

White-box tests that focus on a small, limited scope (usually a single function)
Written by the software developer to ensure code paths and edge cases are covered
Typically short and quickly written, with carefully chosen test parameters
Mock objects are commonly used to isolate the function under test
Ideally written before the function(s) they test, following Test Driven Development principles
#### Integration tests:

Grey-box tests that focus on interactions between objects and interfaces on a limited scope
Written by the software developer to ensure objects/subsystems interact with dependencies correctly
Medium-length and quickly written, typically checking success/failure states and inputs/outputs
Mocking dependencies, shared resources, and IPC is common practice
Ideally written before the object(s) they test, following TDD principles
#### Acceptance tests:

Black-box tests that cover how a user moves through the system on a broader scope
Written by the product owner, client, tester, or developer to ensure client requirements are met
Short and written by outlining the steps the user must take to complete requested functionality
Ideally written by the client or product owner before the UI is developed
Key technologies include manual tests, the Gherkin domain-specific language, and visual regression tools
#### Refinement tests:

Black-box tests that determine if a proposed UI is useful, usable, aesthetically pleasing, identifiable, inspirational, and valuable
Typically written by a designer or UX expert by presenting a UI design to users and gathering data on how they experience it
Beginning refinement testing before any real (non-prototype) code is implemented often reduces the number of design/UI changes later in development
Key technologies include visual difference tools, A/B testing frameworks, and accessibility testing
Other names include UX tests, usability tests, and end-user tests
#### System tests:

Black-box tests that cover the system as a whole on an extremely broad scope
Written by the tester, developer, and product owner to catch regressions, set performance thresholds, and stress-test the system
Results aren't always a strict pass/fail, trends are more important
Ideally written or their parameters chosen before any development work is done
Key technologies include analysis tools and load-testing tools.  


https://archive.openconcept.ca//blog/mparker/overview-software-testing


