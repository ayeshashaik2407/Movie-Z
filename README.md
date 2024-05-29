# Movie-Z: Secure User Authentication and Seamless Movie Experience

## Overview
Movie-z is a web application that provides a secure and user-friendly movie search and management platform. The application focuses on implementing a robust user authentication system to ensure the safety and privacy of user data, while also offering a seamless movie search and personalization experience.

## Features
1. **Secure User Authentication**:
   - Users can securely sign up and sign in to the application using Java Servlets and JSPs.
   - The application utilizes MySQL to store user credentials, ensuring data integrity and security.
   - Password hashing and salting techniques are implemented to protect user passwords.
   - Multi-factor authentication, such as Google Authenticator or Microsoft Authenticator, is integrated to provide an additional layer of security.

2. **Seamless Movie Experience**:
   - Upon successful login, users are directed to the home screen, where they can easily access the movie search functionality and their personalized movie lists.
   - The application provides a user-friendly interface for searching and browsing movies, with features like filtering, sorting, and pagination.
   - Users can create and manage their own personalized movie lists, such as "Watchlist," "Favorites," and "Completed."
   - The application leverages Java Servlets and JSPs to handle user interactions and update the database accordingly.

## Technologies Used
- **Java**: The core programming language used for the application's backend logic.
- **Servlets**: Java Servlets are used to handle HTTP requests and responses, managing user authentication and authorization.
- **JSPs (Java Server Pages)**: JSPs are used to create dynamic web pages and render the user interface.
- **MySQL**: The relational database management system is used to store user credentials, movie data, and personalized user lists.

## Getting Started
1. **Prerequisites**:
   - Java Development Kit (JDK) 8 or higher
   - Apache Tomcat (or any other Java Servlet container)
   - MySQL database

2. **Installation and Setup**:
   - Clone the repository: `git clone https://github.com/ayeshashaik2407/movie-z.git`
   - Set up the MySQL database:
     - Create a new database for the application.
     - Update the database connection details in the application's configuration files.
   - Configure the Apache Tomcat server:
     - Deploy the application to the Tomcat server.
     - Ensure the server is running and accessible.

3. **Running the Application**:
   - Open a web browser and navigate to the application's URL (e.g., `http://localhost:8080/movie-z`).
   - Users can sign up and sign in to the application using the secure authentication system.
   - After successful login, users can access the movie search and personalization features.

## Contribution
Contributions to the Movie-z project are welcome. If you find any issues or have suggestions for improvements, please feel free to submit a pull request or open an issue in the repository.

## License
This project is licensed under the [MIT License](LICENSE).
