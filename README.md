# DB Connection - Java Servlet Project

## 📌 Project Overview

This project is a Java-based web application developed using Java Servlets, JSP, JDBC, and MySQL.

The application demonstrates database connectivity and user registration/login functionality through a web-based interface.

## 🛠️ Technologies Used

- Java
- Java Servlets
- JSP (JavaServer Pages)
- JDBC (Java Database Connectivity)
- MySQL
- HTML
- Apache Tomcat
- Eclipse IDE

## 📂 Project Features

- Establishes a connection between Java and MySQL using JDBC.
- User registration functionality.
- User login functionality.
- Database connection testing.
- JSP-based web pages.
- Servlet-based request processing.
- MySQL database integration.

## 📄 Main Files

| File | Description |
|---|---|
| `DBConnection.java` | Establishes the connection with the MySQL database. |
| `TestConnection.java` | Tests whether the database connection is working. |
| `LoginServlet.java` | Handles user login requests. |
| `RegisterServlet.java` | Handles new user registration. |
| `login.jsp` | Login page. |
| `register.jsp` | Registration page. |
| `home.jsp` | Home page after login. |
| `index.jsp` | Main/index page. |
| `web.xml` | Web application configuration and servlet mapping. |
| `mysql-connector-java-5.1.23.jar` | MySQL JDBC driver. |

## ⚙️ Requirements

- JDK 8 or above
- Apache Tomcat
- MySQL Server
- Eclipse IDE or another Java IDE

## 🚀 How to Run

1. Clone or download this repository.
2. Import the project into Eclipse as a Dynamic Web Project.
3. Configure the MySQL database.
4. Update the database username, password, and database name in `DBConnection.java`.
5. Add the MySQL Connector/J library to the project.
6. Configure Apache Tomcat.
7. Run the project on the Tomcat server.
8. Open the application in a web browser.

## 🔗 Database Connectivity

The project uses JDBC to connect the Java application with MySQL.

The basic connection process is:

**Java Application → JDBC → MySQL Database**

## 👩‍💻 Author

**Fariha Naureen**
