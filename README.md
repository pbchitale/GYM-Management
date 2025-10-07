## 🏋️ Gym Management System

This is a comprehensive, web-based application developed in **Eclipse IDE** to efficiently manage the daily operations of a modern fitness centre. It is built using the core **Java EE** technology stack, demonstrating a robust understanding of full-stack development.

---

### 💻 Technology Stack

| Layer | Technology | Role |
| :--- | :--- | :--- |
| **Frontend/View** | **JSP** (JavaServer Pages) | Renders the dynamic user interface and presentation layer. |
| **Backend/Controller** | **Java Servlets** | Handles HTTP requests, manages control flow, and implements business logic. |
| **Database Connectivity**| **JDBC** (Java Database Connectivity) | Provides the interface for Java code to communicate with the database. |
| **Database/Model** | **SQL** (e.g., MySQL) | Stores and manages all application data (members, subscriptions, etc.). |
| **Server** | **Apache Tomcat** | The web container used for deploying and running the application. |
| **Development Tool** | **Eclipse IDE** | The integrated development environment used for building and managing the project. |

---

### ✨ Core Features

The system offers a complete suite of tools to digitize gym management:

* **Member Management:** Complete CRUD (Create, Read, Update, Delete) functionality for managing member profiles, personal details, and tracking attendance.
* **Subscription & Billing:** Defines and tracks various membership plans, handles enrollments, manages renewals, and tracks payment statuses.
* **Staff & Trainer Oversight:** Maintains records for trainers and staff, allowing for role assignment and scheduling.
* **Class Scheduling:** Creates and manages fitness classes, sets capacity limits, and assigns specific trainers.

---

### 🏛️ Architecture

The project follows the standard **Model-View-Controller (MVC)** design pattern, which promotes maintainability and scalability by separating concerns:

1.  **View (JSP):** Responsible for the visual output and collecting user input.
2.  **Controller (Servlets):** Processes requests from the View, updates the Model, and selects the next View.
3.  **Model (Java/JDBC/SQL):** Manages the application data, business logic, and database interactions.

---

### 🚀 Setup and Running the Project

To set up and run this project, you will need the following tools configured in your environment:

1.  **Prerequisites:**
    * **JDK** (Java Development Kit)
    * **Eclipse IDE** (configured for Java EE development)
    * **Apache Tomcat Server**
    * A **SQL Database** (e.g., MySQL, configured with the appropriate JDBC driver).
2.  **Database Configuration:**
    * Create a database (e.g., `gym_db`).
    * Execute the necessary SQL script (often provided as `schema.sql`) to create all required tables.
    * Update the database connection parameters (URL, username, password) within the appropriate **Java** class (usually a utility or configuration class) in the project source code.
3.  **Deployment:**
    * Import the project into **Eclipse**.
    * Ensure the project is linked to your local **Tomcat** server in Eclipse.
    * Run the application on the server.
4.  **Access:**
    * Open your web browser and navigate to the application URL (e.g., `http://localhost:8080/[Project-Name]/index.jsp`).
