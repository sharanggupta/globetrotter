# Globetrotter

## System Name

Globetrotter

## Contributors

sharanggupta - [https://github.com/sharanggupta](https://github.com/sharanggupta)

## License

MIT License

## Background Context

This is a TDD Sandbox Project to simulate legacy code and practice test-driven development.  Learn more at [Optivem Journal](https://optivem.com/journal) and from [Valentina Jemuović](https://www.linkedin.com/in/valentina-jemuovic/).

## Use Cases

*   Search Flights
*   Search Hotels
*   Plan Trip
*   Book Flights
*   Book Hotels
*   View Trip
*   Cancel Trip

## External Systems

*   Flight API (e.g., Kiwi.com API - Free tier available)
*   Hotel API (e.g., TripAdvisor API - Free tier available)
*   Weather API (e.g., OpenWeatherMap API - Free tier available)
*   Points of Interest API (e.g., Foursquare Places API - Free tier available)
*   System Clock

## Tech Stack

*   Programming Language: Java
*   Framework: Spring Boot
*   Databases: PostgreSQL (per microservice)
*   Message Broker: RabbitMQ

## System Architecture Style

Frontend + Microservice Backend

## Architecture Diagram

[Embed Architecture Diagram Here]

**Components:**

*   Frontend
*   Flight Service
*   Hotel Service
*   Weather Service
*   POI Service

**External Systems:**

*   Kiwi.com API
*   TripAdvisor API
*   OpenWeatherMap API
*   Foursquare Places API
*   System Clock

## Repository Strategy

Mono-Repo approach

## Branching Strategy

Feature Branching

## Deployment Model

Linode shared CPU 2GB cluster

## Component Repositories

Since we are using a Mono-Repo approach, all components will reside in this repository.

## Project Boards

We will use GitHub Projects for managing tasks and issues. [https://github.com/users/sharanggupta/projects/1]

## Tickets

Create tickets in the Project Board for the User Stories. Examples:

*   Search Flights
*   Search Hotels
*   Plan Trip
*   Book Flights
*   Book Hotels
*   View Trip
*   Cancel Trip

## Environments

*   UAT Environment
*   Production Environment

## Automated CI/CD Pipeline

We will set up an automated CI/CD pipeline using GitHub Actions to build, test, and deploy the application to the UAT and Production environments.

## Developer Setup

1.  Install Docker and Docker Compose.
2.  Configure the application using Docker Compose.
