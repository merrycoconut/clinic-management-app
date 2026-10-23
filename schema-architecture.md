# Schema Architecture

## Architecture Summary
This project uses a Three-Tier Software Architecture comprising a Presentation Layer, an Application Layer, and a Data Layer. 

- The Presentation Layer is constructed using HTML5, CSS3, and JavaScript, delivering a lightweight client interface that interacts asynchronously with the server via HTTP/REST endpoints. 

- The Application Layer is powered by a Java-based Spring Boot backend operating on the MVC pattern; Spring REST Controllers manage incoming HTTP requests, apply business logic through dedicated service components, and delegate persistence logic. 

- The Data Layer combines a MySQL relational database managed through JPA/Hibernate for structured transactional data with a MongoDB document database.

## Numbered Flow







