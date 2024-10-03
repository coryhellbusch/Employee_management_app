Employee Management Application

A full-stack web application that allows users to manage employees and departments within an organization. The application provides functionality to manage employees and departments within an organization, as well as to assign employees to specific departments. 

Technologies used: 
Backend: Java (Spring Boot)
Frontend: React.js
Database: MySQL
Other tools: 
- Maven (for dependency management)
- Spring Data JPA (for database interaction)
- Axios (for API communication between frontend and backend)

Installation instructions: 
Prerequisites: 
- Java Development Kit (JDK) 8 or higher
- Node.js and npm
- MySQL
- Maven
Backend setup:
- Clone the repository
- Configure the MySQL database:
  - Create a new MySQL database named employee_management
  - Add the database to the application.properties file
- Run the backend:
  - mvn spring-boot:run
Frontend setup:
- Navigate to the frontend directory
- Install the required packages:
  - npm install
- Run the frontend application:
  - npm start
 
Future enhancements:
- Add authentication and authorization for secure access
- Implement pagination for large data sets
- Add more advanced reporting and analytics on employee data
