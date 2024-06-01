
# Library-Management-System !## Introduction 
A Library Management System designed to see the books available in a college library. It allows students to register as a user and issue/return books from the college library hassle free. The backend is designed as a **Monolithic Architecture** with various nuances as discussed below.
## Technologies and Dependencies Used
* [Maven](https://maven.apache.org/) used as a dependency management tool.
* [Spring Boot](https://spring.io/projects/spring-boot) used to build hassle free web applications and writing REST APIs.
* [Spring Security](https://spring.io/projects/spring-security) used for Authentication and Authorizations.
* [Spring data JPA (Hibernate)](https://hibernate.org/) Used to reduce the time of writing hardcoded sql queries and instead allows to write much more readable and scalable code 
* [MySQL](https://www.mysql.com/) used as a Java persistence store
* [Project Lombok](https://projectlombok.org/) Reduces the time  of writing java boiler plate code.

## Using Library Management System
CLI-->
```
git clone https://github.com/https://github.com/Maha-Mahii/LibraryManagementSystem/Library-Management-System.git
cd Library-Management-System
Eclipse-->
1. Let maven resolve dependencies 
2. run SpringBootApplication

1. **User** having attributes:
* Primary key user_id, name 
2. **Books** having attributes:
* Primary key book_id ,title, author, borrowed and borrowedBy

### Functionalities Exposed 
#### Book Controller class 
The REST APIs exposed are 
* CRUD APIs for the create, update, delete student information. The create book API:
For getting all books and details: **http://localhost:8080/api/books
For getting particular book id details: ** http://localhost:8080/api/books/{id}
For update and delete particular book id details: : ** http://localhost:8080/api/books/{id} have to change the mapping like put or delete.

#### User Controller class
The REST APIs exposed are
*APIs for creating and saving the users.




