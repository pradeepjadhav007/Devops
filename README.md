# Devops
codes and notes 
  Q -  what is the devops ?
  Ans - DevOps is a software development methodology that accelerates the delivery of higher-quality applications and services by combining and automating the work of software 
  development and IT operations teams.

  Q - Cycle of devops ?
  ANS -
Plan - 
In this phase, the team collaborates with the business stakeholders to define the requirements for the project and identify the features that will be delivered.
The goal is to clearly understand the needs and expectations of the stakeholders.
This phase involves creating a roadmap, defining milestones, and setting project goals. An example of this phase in action could be a team using a project management tool like Jira to create a backlog of user stories and tasks.

Code -
In this phase, the development team creates the code for the application. This involves using best practices to write high-quality, maintainable code that can be easily tested. 
The team may use a version control system like Git to manage the codebase. An example of this phase in action could be a team using an integrated development environment (IDE) like Visual Studio Code/ Eclipse to write and debug code.

Build - 
In this phase, the code is compiled and built into executable binaries or packages. This phase includes tasks such as compiling code, running unit tests, and packaging the application. 
An example of this phase in action could be a team using a tool like Jenkins / GitLab to automate the build process, ensuring that code changes are integrated and tested regularly

Test -
In this phase, the application is tested to ensure that it meets the quality standards and requirements. This includes testing at various levels, such as unit tests, integration tests, and acceptance tests. 
An example of this phase in action could be a team using a test automation tool/ platforms like TestSigma/Selenium/Playwright/Cypress to run automated tests for the web application

Release -
In this phase, the application code undergoes a final check for production readiness. If all requirements are met and any identified issues are resolved, the project proceeds to the deployment phase.
By conducting thorough testing, quality assurance, and preparation activities, organizations can ensure that the released application meets quality standards and is ready for end-users to utilize.   
An example of this phase in action could be a team using Jenkins / Bamboo that automates the entire release process.

Deploy -
In this phase, the application is deployed to the desired environment which can be stage, UAT or production environment. This involves setting up the infrastructure, configuring the environment, and deploying the application code. 
An example of this phase in action could be a team using a deployment automation tool like Ansible / Chef to deploy the application across different environments.
Additionally, tools like Kubernetes and Docker are used to establish Continuous deployment pipelines for containerization and orchestration

Operate -
In this phase, the application is monitored and maintained in the production environment. Operations teams monitor the application’s performance, availability, and security, and respond to any incidents or issues that arise
An example of this phase in action could be a team using monitoring tools like Nagios, Prometheus, and ELK stack (Elasticsearch, Logstash, Kibana) to help in monitoring and logging application metrics and logs.

Monitor -
In this phase, the application is monitored and maintained in the production environment. This includes tasks such as monitoring performance, tracking user behavior, and troubleshooting issues. 
Monitoring tools like Grafana, Datadog, and ELK stack (Elasticsearch, Logstash, Kibana) provide visualizations, alerts, and dashboards for proactive monitoring and troubleshooting.

Q - Monolithic architecture

Monolithic architecture is a traditional approach in system design where all components of an application are integrated into a single codebase. In this unified structure, the entire application—including the user interface, business logic, and data access layers—is developed, deployed, and maintained as a single entity1. Despite facing competition from more modern architectural styles like microservices, monolithic systems still hold importance in various contexts:

Simplicity: Monolithic architectures offer straightforward development and deployment processes. With all components bundled together, it’s often easier for developers to understand the system as a whole and make changes.

Cost-Effectiveness: For small to medium-sized projects or startups, monolithic architectures can be more cost-effective. They require less infrastructure overhead and simpler deployment setups compared to distributed systems.

Performance: In some cases, monolithic systems can provide better performance due to reduced communication overhead between components, as everything runs within the same process.

Security: With fewer inter-service communication points, monolithic systems may have a reduced attack surface, potentially making them more secure if proper security measures are implemented.

Legacy Support: Many existing systems still rely on monolithic architectures, necessitating expertise in understanding and maintaining them1.

Q - Microservices architecture
Microservices architecture (often shortened to microservices) refers to an architectural style for developing applications. In this approach, a large application is broken down into smaller, independent parts called microservices, each with its own realm of responsibility. These microservices can communicate with each other to serve a single user request. Here are some key points about microservices architecture:

Independence: Each microservice is a single service built to accommodate a specific application feature or handle discrete tasks. They communicate with other services through simple interfaces to solve business problems.

Benefits:
Speed: Microservices allow faster application development.
Scalability: You can scale individual microservices independently.
Flexibility: Different technology stacks can be used for each microservice.
Isolation: Failures in one microservice don’t affect others.


Examples:

Website Migration: Complex websites hosted on monolithic platforms can be migrated to cloud-based and container-based microservices platforms.
Media Content: Images and video assets can be stored in scalable object storage systems and served directly to web or mobile using microservices.
Transactions and Invoices: Payment processing and ordering can be separated into independent units of services.
Data Processing: Microservices platforms can extend cloud support for existing modular data processing services.


