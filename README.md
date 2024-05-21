# Boardgame-WebApplication (FullStack)



## Description

**Board Game Database Full-Stack Web Application.**
This web application serves as a comprehensive database for board games and their reviews. It offers the following features:

Viewing Board Games and Reviews: Anyone can browse the list of the board games and read the reviews without logging in.

<img align="right" alt="Coding" width="400" src="https://github.com/Sharadvanth/FullStack-WebApp-DevOps/blob/main/!NEW.gif
">
User Login: Users must log in to contribute to the database.


User Roles and Permissions:
	- Users: Logged-in users can add new board games to the list and 	submit their reviews.
	- Managers: In addition to the abilities of regular users, managers have  the authority to edit or delete any reviews

## Technologies

Frontend: Thymeleaf, Thymeleaf Fragments, HTML5, CSS, JavaScript, Twitter Bootstra
Backend: Java, Spring Boot, Spring MVC, JDBC, H2 Database Engine, Spring Security
Cloud Services: AWS EC2
Testing: JUnit test framework.
Build Tools: Maven



### Full-Stack Application Charecteristics

- **UI Components**
  - Created with Thymeleaf
  - Styled with Twitter Bootstrap

- **Authentication and Authorization**
  - Using Spring Security
  - Authentication with username and password
  - Authorization by granting different permissions based on roles (non-members, users, managers)
  - Different roles with varying levels of permissions:
    - **Non-members:** Can only see the board game lists and reviews
    - **Users:** Can add board games and write reviews
    - **Managers:** Can edit and delete reviews

- **Deployment**
  - Deployed on AWS EC2

- **Testing**
  - JUnit test framework for unit testing

- **Architecture**
  - Spring MVC best practices to segregate views, controllers, and database packages

- **Database**
  - JDBC for database connectivity and interaction
  - CRUD (Create, Read, Update, Delete) operations for managing data
  - `schema.sql` file to customize the schema and input initial data

- **Thymeleaf Fragments**
  - Used to reduce redundancy of repeating HTML elements (head, footer, navigation)

