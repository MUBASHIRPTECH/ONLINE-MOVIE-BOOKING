
# Movie Seat Booking System
The Movie Seat Booking System is a web application built with Java and Spring Boot, allowing users to browse available movies and book seats for their desired shows. The system provides a seamless user experience and efficient backend management for movie theaters.
# Table of Contents
    • Technologies
    • Features
    • Getting Started
        ◦ Prerequisites
        ◦ Installation
    • Usage
    • Contributing
    • License
# Technologies

    • Java:   The primary backend language.
    
    • Spring Boot: A powerful framework for building Java-based applications.
    
    • Spring Data JPA: Provides easy integration with JPA (Java Persistence API) for data access.
    
    • Hibernate: An additional ORM (Object-Relational Mapping) framework that can be used alongside Spring Data JPA for database interaction and 
                 management.
                 
    • Thymeleaf: A modern server-side Java template engine for web and standalone environments, used for rendering HTML templates.
    
    • HTML and CSS: Frontend technologies for creating interactive user interfaces.
    
    • Bootstrap: A popular CSS framework that simplifies the process of making web pages responsive and visually appealing.
    
    • REST API: A software architectural style for building scalable web services. This can be implemented using Spring Boot to create RESTful APIs.
    
    • MySQL Database: A popular open-source relational database management system, used for storing and managing your application's data.
      
# Features

    • Browse Movies: Users can view a list of available movies.
    
    • Seat Selection: Interactive seat selection interface for users to choose their seats.
    
    • Booking Management: Efficient booking management system for theater administrators.
    
    • User Authentication: Secure user authentication and session management.
    
# Getting Started

# Prerequisites
Make sure you have the following tools installed:

    • Java Development Kit (JDK)
    
    • Maven or Gradle build tools
    
    • IDE such as Eclipse, IntelliJ, or Spring Boot IDE
    
    • MySQL database server
    
# Installation
    1. Clone the Repository:
       git clone <repository-url>
       
    2. Database Configuration:
        ◦ Create a MySQL database and update the application.properties file in the src/main/resources directory with your database credentials.
        
       spring.datasource.url=jdbc:mysql://<database-host>:<port>/<database-name>
       spring.datasource.username=<username>
       spring.datasource.password=<password>
       
    3. IDE Configuration:
        ◦ Import the project into your preferred IDE (Eclipse, IntelliJ, or Spring Boot IDE).
        
    4. Build and Run:
        ◦ Build and run the application from your IDE or use Maven/Gradle command line:
         mvn spring-boot:run  or  gradle bootRun
# Usage
Once the application is running, open a web browser and navigate to http://localhost:8080 to access the movie seat booking system. Follow the on-screen instructions to select and book seats for the desired movie show.

# Contributing
Feel free to contribute to the project by opening issues or creating pull requests. Your feedback and suggestions are welcome!

# All Screenshorts

<img width="1470" alt="Screenshot 2023-11-08 at 1 15 29 AM" src="https://github.com/MUBASHIRPTECH/Socialbook_Project/assets/146514174/b5160707-71f5-4fbd-9d67-a0dfc5b0800d">
<img width="1470" alt="Screenshot 2023-11-08 at 1 18 46 AM" src="https://github.com/MUBASHIRPTECH/Socialbook_Project/assets/146514174/79ebd5e7-1d47-49b9-9ae3-5dd549118e56">
<img width="1470" alt="Screenshot 2023-11-08 at 1 18 57 AM" src="https://github.com/MUBASHIRPTECH/Socialbook_Project/assets/146514174/c855a254-2ea1-4088-8924-e6bf19ddd5c7">
<img width="1470" alt="Screenshot 2023-11-08 at 1 19 24 AM" src="https://github.com/MUBASHIRPTECH/Socialbook_Project/assets/146514174/a3f4f4a4-ab7a-41e2-9b95-32ef121f9d0d">
<img width="1470" alt="Screenshot 2023-11-08 at 1 19 34 AM" src="https://github.com/MUBASHIRPTECH/Socialbook_Project/assets/146514174/751e9700-7ade-499d-96a6-639aea6ecf81">
<img width="1470" alt="Screenshot 2023-11-08 at 1 19 51 AM" src="https://github.com/MUBASHIRPTECH/Socialbook_Project/assets/146514174/13f87c5c-a52b-4834-98ba-c60b4c628bf2">


# License

This project is licensed under the MIT License.



