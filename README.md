# Servlet-Based User Authentication with MariaDB

This Java web project demonstrates a simple yet effective user authentication system using servlets and a MariaDB database. The project includes components for a login page, login servlet, and a home servlet.

## Features

- Securely connect to a MariaDB database using ServletContext parameters.
- Authenticate users based on their email and password.
- Forward users to the home page upon successful login or back to the login page on failure.
- Demonstrate proper resource management and error handling.
- Leverage Jakarta EE (formerly Java EE) and the MariaDB JDBC driver for web development.

## Getting Started

1. **Database Setup:** Set up a MariaDB database and configure the connection parameters in the `web.xml` file.

2. **Server Deployment:** Deploy the project to a Jakarta EE-compatible server (e.g., Apache Tomcat).

3. **User Authentication:** Access the project's login page (`Login.html`) to enter your email and password.

4. **Home Page:** Upon successful login, you will be directed to the home page (`HomeServlet`) with a welcome message.



