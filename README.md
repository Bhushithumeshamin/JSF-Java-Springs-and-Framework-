📘 E-Book Management System

An automated, web-based solution designed to streamline book inventory management for administrators and provide a seamless browsing experience for users.
This project was developed as part of the Java and Spring Framework Lab (CS3603-1) at NMAM Institute of Technology.

📋 Project Overview

The E-Book Management System addresses the inefficiencies of manual book management by providing a centralized digital platform.
It enables effective inventory control for administrators and an intuitive book discovery experience for users, bridging the gap between traditional methods and modern automation.

🚀 Features
👨‍💼 Administrator Features

Inventory Control
Perform full CRUD (Create, Read, Update, Delete) operations to manage:
Book titles
Authors
ISBN
Pricing
Stock levels
Secure Access
Restricted administrator login ensures that only authorized personnel can modify inventory data.
Real-time Management
A dedicated admin dashboard allows quick updates and removals using streamlined forms.

👤 User Features

Dynamic Search
Keyword-based search to locate books by:

Title

Author

Category

Categorization
Users can browse collections filtered by genres or themes.

Responsive UI
The interface is accessible across multiple devices including:

Desktop

Tablet

Mobile

🛠️ Technical Stack

Backend: Spring Boot

Frontend: Thymeleaf (Template Engine), Bootstrap, CSS

Database: H2 In-Memory Database (for development and testing)

Architecture: Three-layered architecture

Presentation Layer

Service Layer

Repository Layer

⚙️ Implementation Details

Persistence Layer
Implemented using Spring Data JPA with entity mapping for book attributes such as:

Price

Quantity

Publisher

Search Logic
Uses findByTitleContainingIgnoreCase for flexible and case-insensitive search queries.

Data Handling & Debugging
Hibernate logging is enabled (DEBUG/TRACE) to monitor SQL execution and improve debugging efficiency.

🔮 Future Enhancements

Migration from H2 in-memory database to persistent databases such as MySQL or PostgreSQL.

Integration of secure payment gateways for direct e-book purchases.

Implementation of Role-Based Access Control (RBAC) using Spring Security.

Deployment of the application on cloud platforms for global accessibility.
