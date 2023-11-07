
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

<img width="1470" alt="Screenshot 2023-11-08 at 1 25 20 AM" src="https://github.com/MUBASHIRPTECH/ONLINE-MOVIE-BOOKING/assets/146514174/e690c938-a744-4373-901c-3e85f5fefd13">
<img width="1470" alt="Screenshot 2023-11-08 at 1 25 27 AM" src="https://github.com/MUBASHIRPTECH/ONLINE-MOVIE-BOOKING/assets/146514174/0d52eb8d-9bb0-48bb-9c19-e8491ba59512">
<img width="1470" alt="Screenshot 2023-11-08 at 1 25 36 AM" src="https://github.com/MUBASHIRPTECH/ONLINE-MOVIE-BOOKING/assets/146514174/1b5fed65-1d99-48bc-b39d-c6598a877ec8">
<img width="1470" alt="Screenshot 2023-11-08 at 1 25 52 AM" src="https://github.com/MUBASHIRPTECH/ONLINE-MOVIE-BOOKING/assets/146514174/d28c6a86-b9f7-4128-8a81-3074ebe1fc2c">
<img width="1470" alt="Screenshot 2023-11-08 at 1 25 59 AM" src="https://github.com/MUBASHIRPTECH/ONLINE-MOVIE-BOOKING/assets/146514174/2b28836a-8cbd-4cf8-b728-31d24d02fc36">
<img width="1470" alt="Screenshot 2023-11-08 at 1 26 10 AM" src="https://github.com/MUBASHIRPTECH/ONLINE-MOVIE-BOOKING/assets/146514174/b5c468a7-d427-473f-84d7-60d30f5b8827">
<img width="1470" alt="Screenshot 2023-11-08 at 1 26 21 AM" src="https://github.com/MUBASHIRPTECH/ONLINE-MOVIE-BOOKING/assets/146514174/895a26f1-cef0-4b1f-bd5d-212507d56dd9">
<img width="1470" alt="Screenshot 2023-11-08 at 1 27 12 AM" src="https://github.com/MUBASHIRPTECH/ONLINE-MOVIE-BOOKING/assets/146514174/2e7f042f-823d-4166-99e1-30ab63c41656">
<img width="1470" alt="Screenshot 2023-11-08 at 1 27 16 AM" src="https://github.com/MUBASHIRPTECH/ONLINE-MOVIE-BOOKING/assets/146514174/dffa3a2b-342c-4f1d-827f-4caba4ed29fe">
<img width="1470" alt="Screenshot 2023-11-08 at 1 27 24 AM" src="https://github.com/MUBASHIRPTECH/ONLINE-MOVIE-BOOKING/assets/146514174/8cec9f9c-e666-4d4b-8ad5-9b97b3d2bb2f">
<img width="1470" alt="Screenshot 2023-11-08 at 1 27 27 AM" src="https://github.com/MUBASHIRPTECH/ONLINE-MOVIE-BOOKING/assets/146514174/a996b846-9370-4ec4-9a67-32bc7e32394f">



# License

This project is licensed under the MIT License.



