# -Doctor-Patient-Portal-JavaWebProject
# Doctor-Patient Portal

## Overview
The *Doctor-Patient Portal* is a web-based application developed in *Java (Servlets, JSP, DAO)* with *Maven* for managing doctor-patient interactions efficiently. The system enables patients to book appointments, doctors to manage their schedules, and administrators to oversee user management.

## Features
### Admin
- Manage doctors (Add, Update, Delete)
- Manage specialists
- View and manage appointments

### Doctor
- Login/logout functionality
- Update profile and password
- View and update appointment status

### Patient
- Register and login/logout
- Book and manage appointments

## Technologies Used
- *Backend:* Java Servlets, JSP, DAO Pattern
- *Database:* MySQL
- *Build Tool:* Maven
- *Web Server:* Tomcat

## Installation & Setup
### Prerequisites
- Install *JDK 8+*
- Install *Apache Tomcat 9+*
- Install *MySQL* and create a database
- Install *Maven*

### Steps to Run
1. Clone the repository:
   sh
   git clone https://github.com/tanisha15mishra/Doctor-Patient-Portal.git
   
2. Navigate to the project directory:
   sh
   cd Doctor-Patient-Portal
   
3. Import the project as a *Maven Project* in your IDE (Eclipse/IntelliJ IDEA).
4. Update the database credentials in DBConnection.java.
5. Build and deploy the project:
   sh
   mvn clean install
   
6. Deploy the WAR file to *Tomcat*.
7. Start Tomcat and access the application at:
   
   http://localhost:8080/Doctor-Patient-Portal
   

## Contributors
- [TANISHA MISHRA](https://github.com/tanisha15mishra))

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
