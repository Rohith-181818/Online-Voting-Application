# Online-Voting-Application

🗳️ Online Voting Application
The Online Voting Application is a web-based platform designed to streamline and digitize the voting process. Built using Java (Spring Boot) and backed by a relational database (PostgreSQL), this application enables users to register, cast their votes securely, and view election results in real-time.

🚀 Features
User Registration & Authentication
Secure login system for voters using unique credentials.

Candidate Management
Admins can add, update, or remove candidates for elections.

Voting System
Authenticated voters can cast their vote once per election.

Election Results
Real-time vote counting and winner display functionality.

Admin Dashboard
View and manage voter and candidate data efficiently.

🛠️ Tech Stack
Backend: Java, Spring Boot

Database: PostgreSQL

Tools: Maven, JPA/Hibernate

API Testing: Postman


📂 Project Structure
Entity/ – Data models (Voter, Candidate, Voting, ElectionResult)

Repository/ – JPA Repositories for DB operations

Service/ – Business logic layer

Controller/ – RESTful APIs for frontend/backend interaction

application.properties – Configuration for DB and server

📦 How to Run
Clone the repository

Configure your database settings in application.properties

Run using your preferred IDE or mvn spring-boot:run

Test APIs using Postman

📌 Future Enhancements
Email verification for voter registration

Role-based authentication (Admin vs Voter)

UI frontend with Angular/React
