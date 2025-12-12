> **💰 Final Project OOP: Expense Tracker Program** 

![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Maven](https://img.shields.io/badge/apache_maven-C71A36?style=for-the-badge&logo=apachemaven&logoColor=white)
![Servlet](https://img.shields.io/badge/Java_Servlet-007396?style=for-the-badge&logo=java&logoColor=white)
![Tomcat](https://img.shields.io/badge/Apache_Tomcat-F8DC75?style=for-the-badge&logo=apachetomcat&logoColor=black)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)
![Status](https://img.shields.io/badge/build-passing-brightgreen?style=for-the-badge)

---

## Team Members

| Nama           | NRP        | 
| ---            | ---        | 
| Muhammad Abid Baihaqi Al Faridzi | 5025241133 |
| Lyonel Oliver Dwiputra         | 5025241145 |
| Hosea Felix Sanjaya            | 5025241177 |

---

## Project Overview (Description)

The Expense Tracker is a comprehensive web-based application designed to address the challenges of personal financial management. In an era where digital transactions are ubiquitous, maintaining financial literacy and tracking daily expenditures is crucial. This application provides a robust solution for users to record, monitor, and analyze their financial activities efficiently.

Built upon the principles of Object-Oriented Programming (OOP), the system utilizes the Model-View-Controller (MVC) architectural pattern. This ensures a strict separation of concerns, resulting in a codebase that is modular, scalable, and easy to maintain. The project demonstrates the practical application of Java enterprise technologies, database management, and secure web development practices.

---

## Technologies Used

- **Java**: The core programming language used for building the application.
- **Java Servlet**: For handling HTTP requests and responses.
- **Apache Tomcat**: A web server to deploy and run the Java Servlet application.
- **Apache Maven**: For project management and build automation.
- **MySQL**: The database management system used to store user and expense data.
- **HTML/CSS/JavaScript**: For front-end development and user interface design.

---

## Features

Backend Core
- Java Development Kit (JDK) 17: Serves as the foundation for the application logic, leveraging strong typing and modern OOP features.
- Java Servlet API: Functions as the Controller layer, managing HTTP requests, session handling, and application routing.
- Hibernate ORM: Implements the Object-Relational Mapping technique to bridge the gap between Java objects and the relational database, eliminating boilerplate SQL code.

Infrastructure and Build Tools
- Apache Maven: Manages project dependencies, build lifecycles, and project structure standardization.
- Apache Tomcat: Acts as the servlet container and web server for deploying the compiled application.

Data Persistence
- MySQL: A relational database management system used for persistent storage of user credentials and transaction records.

Frontend Interface
- HTML5, CSS3, and JavaScript: Provides a responsive and interactive user interface, featuring dynamic DOM manipulation and theme management (Dark/Light mode).

---

## System Design (Classes)

Data Access Layer (DAO Pattern)
This layer isolates the application/business layer from the persistence layer.
- UserDao: Manages all database operations related to user accounts, including authentication verification and profile updates.
- ExpenseDao: Handles the lifecycle of expense records. It encapsulates complex queries for filtering, sorting, and aggregating financial data.
- NotificationDao: Responsible for persisting and retrieving user system notifications.

Entity Layer (Models)
These classes represent the data structure and map directly to database tables via Hibernate annotations.
- User: Represents the application user, storing credentials and profile information.
- Expense: The core entity containing transaction details such as amount, category (ENUM), date, and description.
- Notification: Represents alerts or messages intended for the user.

Utility and Configuration
- HibernateUtil: A utility class implementing the Singleton pattern. It configures the Hibernate SessionFactory and manages database connections to ensure resource efficiency and thread safety.

---

## How to Run

### Prerequisites:
- Java Development Kit (JDK 17 or higher)
- Apache Maven installed and configured in system PATH
- Apache Tomcat server (version 7 or higher)
- MySQL database server installed and running

### Installation Steps:
1. Clone the repository:
   ```bash
   git clone https://github.com/abidalfrz/final-project-pemrograman-berorientasi-objek.git
    ```
2. Navigate to the project directory:
   ```bash
   cd final-project-pemrograman-berorientasi-objek/Expense_Tracker
   ```
3. Create a new MySQL database, for example `expense_tracker`.
4. Configure database connection:
   - Open the `src/main/java/util/HibernateUtil.java` file.
   - Update the database URL, username, and password to match your MySQL configuration.
5. Run the application:
   ```bash
   mvn tomcat7:run
   ```
6. Open your web browser and go to:
   ```
   http://localhost:8080/Expense_Tracker
   ```
---

## Screenshots

### Login Page

| Light Mode | Dark Mode |
| :---: | :---: |
| ![L-Login](assets/L-Login.jpeg) | ![D-Login](assets/D-Login.jpeg) |

### Register Page

| Light Mode | Dark Mode |
| :---: | :---: |
| ![L-Register](assets/L-Register.jpeg) | ![D-Register](assets/D-Register.jpeg) |

### Home Page

| Light Mode | Dark Mode |
| :---: | :---: |
| ![L-Home](assets/L-Home.jpeg) | ![D-Home](assets/D-Home.jpeg) |

### Dashboard Page

| Light Mode | Dark Mode |
| :---: | :---: |
| ![L-Dashboard](assets/L-Dashboard.jpeg) | ![D-Dashboard](assets/D-Dashboard.jpeg) |

### Add Expense Page

| Light Mode | Dark Mode |
| :---: | :---: |
| ![L-AddExpense](assets/L-AddExpense.jpeg) | ![D-AddExpense](assets/D-AddExpense.jpeg) |

### Exported Results

![ExportResults](assets/ExportResults.jpeg)

### Link GitHub

https://github.com/abidalfrz/final-project-pemrograman-berorientasi-objek

### Link Youtube

https://youtu.be/mZNt2BdwFX0

---

## Conclusion

The Expense Tracker project serves as a testament to the practical application of advanced software engineering principles, specifically focusing on Object-Oriented Programming (OOP) and the Model-View-Controller (MVC) architecture. By successfully integrating Java Servlets, Hibernate ORM, and MySQL, the development team has delivered a robust, secure, and user-centric solution for personal financial management.

This project not only addresses the real-world problem of financial tracking but also demonstrates the scalability and maintainability of enterprise-grade Java applications. The strict separation of concerns achieved through the DAO pattern and layered architecture ensures that the codebase remains clean and adaptable for future iterations.

Looking ahead, this application establishes a solid foundation for potential enhancements. Future development roadmaps could include the integration of Machine Learning for predictive spending analysis, the development of a native mobile application companion, and direct API integration with banking services to automate transaction recording. Ultimately, this project highlights the critical role of structured programming in building reliable and efficient web software.
