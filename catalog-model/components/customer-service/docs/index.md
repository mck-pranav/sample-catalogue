# Customer Microservice

This project is a microservice implemented in Spring Boot for managing customer information. It integrates with an internal Enterprise Service Bus (ESB) layer implemented in Apache Camel, which in turn communicates with various services as needed.

## Overview

The Customer Microservice provides functionalities for creating and retrieving customer information. It is designed to integrate seamlessly with other services within the bank's ecosystem.

## Features

- **Customer Management:** Create and retrieve customer information.
- **Integration with ESB:** Communicate with the internal ESB layer implemented in Apache Camel.

## Architecture

The microservice follows a layered architecture:

1. **Controller and Service Layer:** Implements business logic and exposes REST endpoints for interacting with customer information.
2. **ESB Layer (Apache Camel):** Routes messages between the microservice and various internal services as needed.

## Prerequisites

- Java 11 or higher
- Apache Camel
- Spring Boot