# Video Link: https://www.loom.com/share/4d53a5a1f89843348429b5e99f556866?sid=6b42ad21-958f-4416-9541-e0ccde47e804

# Event Management System

The **Event Management System** is a web application designed to streamline the process of managing events, participants, and notifications. It provides an easy-to-use interface for event creation, RSVP management, scheduling, and notifications, with robust authentication and administration tools.

## Features

- **Event Creation**: Easily create and manage events.
- **RSVP Management**: Track participant attendance for each event.
- **Scheduling & Reminders**: Set event dates, times, and automated reminders.
- **Notification System**: Send in-app notifications for important updates.
- **Admin Dashboard**: Manage events, notifications, and users via an admin interface.
- **User Authentication**: Secure login, signup, and logout functionality for users.
- **Activity Tracking**: Track user activity for better insights.

## Technologies Used

- **Spring Boot**: Backend framework for building Java-based applications.
- **Spring Security**: Provides authentication and authorization features.
- **Spring Data JPA**: Simplifies data access using the Java Persistence API (JPA).
- **Thymeleaf**: Server-side Java template engine for dynamic web pages.
- **MySQL**: Relational database management system for storing event data.
- **Maven**: Dependency management and build automation tool for Java projects.

## Prerequisites

Before you begin, ensure you have met the following requirements:

- **JDK 17+**: Make sure Java is installed and `JAVA_HOME` is set.
- **Maven**: Ensure Maven is installed for building the project.
- **MySQL**: Set up a MySQL database and configure it in `application.properties`.


## Getting Started

### 1. Clone the Repository or Download the Zip file

```
git clone https://github.com/Ankit17028/Event-Management-System.git
```

### 2. Set Up MySQL Database

# Create a MySQL database for the application also make sure to change the database name:

```
CREATE DATABASE event_management_system;
```

Update application.properties with your MySQL credentials:

properties

```
server=8080
spring.datasource.url=jdbc:mysql://localhost:3306/event_management_system
spring.datasource.username=root
spring.datasource.password=yourpassword
spring.jpa.hibernate.ddl-auto=update
```

### 3. Build the Project

Run the following command to build the project:

```
mvn clean install
```

### 4. RUN DIRECTLY FROM THE main() or make sure to build your application first before running and Converge it any error occurs

### OR 

### 5. Run the Application

```
mvn spring-boot:run
```

### 6. Access the Application

Open your browser and navigate to:

```
http://localhost:8080
```

```
http://localhost:8080/home
```

```
http://localhost:8080/login
```

```
http://localhost:8080/dashboard
```

```
http://localhost:8080/logout
```


### 7. Admin Dashboard
Access the admin dashboard to manage events and users:

```
http://localhost:8080/dashboard
```

### 8. Display Events Profile

```
http://localhost:8080/displayProfile
```

### 9. Display Events

```
http://localhost:8080/displayEvents
```


