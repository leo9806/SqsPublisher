# SQS Customers Service

This repository contains the implementation of an AWS Simple Queue Service (SQS) based application that handles customer data. It is divided into three main components:

1. **Customers.Api**: This is the main API that handles customer related requests. It contains several important sub-components such as:

    - Contracts: The interfaces and data contracts used in the API.
    - Controllers: The controllers that handle HTTP requests.
    - Database: The implementation of the database access layer.
    - Domain: The core business logic and domain entities.
    - Mapping: The mapping profiles for object-to-object mapping.
    - Messaging: The implementation of the messaging system.
    - Properties: The application properties and configurations.
    - Repositories: The implementations of the data repositories.
    - Services: The services that implement the business logic.
    - Validation: The classes responsible for input validation.

2. **Customers.Consumer**: This component consumes messages from the queue, with key elements including:

    - Handlers: The handlers that process the messages from the queue.
    - Messages: The message classes that represent the data sent over the queue.
    - Properties: The application properties and configurations.

This project is an excellent example of a distributed system that uses AWS SQS for handling asynchronous messaging between components. 
