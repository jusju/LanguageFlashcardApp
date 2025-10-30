## Flashcard App
A full-stack learning app with focus on backend where users create and practice flashcards, with secure authentication, email verification, and admin tooling. Built with Spring Boot 3, Thymeleaf, Spring Security, Spring Data JPA, and MySQL.

#### Overview
This project is a Spring Boot web application that lets learners create, edit, and practice language flashcards. It implements a features such as registration, login, email verification, password reset, role-based access (USER/ADMIN), a simple practice mode, and CRUD for flashcards with tests.

The codebase demonstrates development skills:
- Backend: Spring Boot, Spring MVC, Spring Data JPA, Spring Security 6
- Frontend: Thymeleaf with Bootstrap styling
- Infrastructure: MySQL, JavaMail
- Quality control: Repository tests, environment-based config

#### Tech Stack
- Language: Java 17
- Frameworks: Spring Boot 3, Spring MVC, Spring Security 6, Spring Data JPA
- Templating: Thymeleaf + Bootstrap
- Database: MySQL
- Build: Maven
- Mail: JavaMail (SMTP)

#### Features
- Sign up with email and password
- Email verification before first login
- Login/Logout with Spring Security 6
- Forgot password and password reset via emailed token
- Create, read, update, delete flashcards
- Admin-only user list and management views
- Password hashing
- MySQL db for presistance

### Running the App
1. Configure the database by updating src/main/resources/application.properties to your credentials
2. Configure email if you want to test verification/reset emails
3. Run the app by using `mvn spring-boot:run`
