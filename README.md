# Employee CRUD App


## Description
The Employee CRUD App is a Spring Boot web application that provides functionality to manage employee records. Users can perform basic CRUD (Create, Read, Update, Delete) operations on employee data. The application demonstrates the integration of Spring Boot with Thymeleaf, Hibernate, and a relational database.
## Features
- **Create**: Add a new employee with details like first name, last name, and email.
- **Read**: View a list of all employees.
- **Update**: Modify existing employee details.
- **Delete**: Remove an employee from the database.
- Dynamic user interface with Thymeleaf templates.
- Responsive design using Bootstrap.

## Technologies Used
- **Backend**: Java, Spring Boot (Spring MVC, Spring Data JPA)
- **Frontend**: Thymeleaf, HTML, CSS, Bootstrap
- **Database**: MySQL or H2 (configurable)
- **Build Tool**: Maven

## Prerequisites
- Java 11 or later
- Maven 3.6 or later
- MySQL 
- Git


## Setup Instructions
1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/Employee-CRUD.git
   cd Employee-CRUD
2. Configure the database:
- Open `src/main/resources/application.properties`.
- Set up your database credentials (for MySQL).

For MySQL:
   ```properties
  spring.datasource.url=jdbc:mysql://localhost:3306/employee_crud_db
  spring.datasource.username=your_username
  spring.datasource.password=your_password
  ```
3. Run the application: To run the application, use the following command:
  ```bash
   mvn spring-boot:run
   ```
4. Access the application:
- Open a browser and navigate to http://localhost:8080/employees/list.

## Usage
- To add a new employee, click the **Add Employee** button.
- To update an employee, click the **Update** button next to the employee's record.
- To delete an employee, click the **Delete** button and confirm the action.

# Screenshots

- **Home Page**:
  ![Home Page Screenshot](https://github.com/flop-signing/Employee-CRUD/blob/5b6a63c829555c9fdd12faaebf7ebf84777f8afd/homepage.png)

- **Add Employee**:
  ![Add Employee Screenshot](https://github.com/flop-signing/Employee-CRUD/blob/5b6a63c829555c9fdd12faaebf7ebf84777f8afd/Addemployee.png)
