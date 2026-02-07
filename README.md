Project Overview

This project is a simple Java Spring Boot backend application that implements a RESTful API for managing items similar to an e-commerce platform (like Flipkart).

The application supports:

Adding new items

Fetching item details by ID

Input validation

In-memory data storage using ArrayList

No database is used; data is stored temporarily in memory.

🧰 Technology Stack

Java 17

Spring Boot

Spring Web

Maven

REST API

In-Memory Storage (ArrayList)
This is a simple Spring Boot REST API for managing items similar to an e-commerce application. 
The application allows adding new items and retrieving item details by ID.

To run the application, Java and Maven are required. 
Use the command: mvn spring-boot:run. 
The application runs on http://localhost:8080.

API Endpoints:
POST /api/items – Adds a new item (name, description, price are required).
GET /api/items/{id} – Retrieves an item by its ID.

The application uses an in-memory ArrayList to store items, with auto-generated IDs.
Input validation is implemented using Jakarta Validation annotations.
No database is used.
