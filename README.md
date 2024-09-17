
# Student Management System 

This project is a Student Management System built using Spring Boot, Hibernate, and Thymeleaf. The system allows for managing student records efficiently, including operations such as adding, updating, deleting, and viewing student details.

Features Add New Student: Allows the addition of new student records. Update Student Information: Modify existing student details. Delete Student: Remove student records from the system. View Student List: Display all registered students in a tabular format. Technologies Used Spring Boot: Framework to create stand-alone, production-grade Spring-based applications. Hibernate: ORM framework for database interaction. Thymeleaf: Java template engine for web applications. MySQL: Relational database management system. Dependencies The project uses the following dependencies:

Spring Web: For building web applications, including RESTful services. Spring Data JPA: For simplifying the database access. MySQL Driver: For connecting to MySQL databases. Thymeleaf: For rendering dynamic content on the front end.
## Installation step



- Clone the repository: git clone https://github.com/kunwaraman/student-management-system.git
- Navigate to the project directory: cd student-management-system

- Install the necessary dependencies using Maven: mvn clean install

- Configure the database connection in the application.properties file: properties spring.datasource.url=jdbc:mysql://localhost:3306/yourdbname spring.datasource.username=yourusername spring.datasource.password=yourpassword spring.jpa.hibernate.ddl-auto=update

- Run the application: mvn spring-boot:run

- Access the application in your browser at http://localhost:8080.
