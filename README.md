# PGLife-
Welcome to PG Life – a Java-based platform designed to simplify the search and management of paying guest (PG) accommodations. This project demonstrates core Java concepts, backend development, and basic web features to simulate a modern rental property portal for students and working professionals.

🚩 Overview
PG Life allows users to:

View and search available PGs by location.

Filter by amenities, price, and gender preference.

Register as new users (students, owners).

Post new PGs (for owners).

Book beds (for students/tenants).

View booking history and PG details.

The project is suitable for learning database integration, authentication modules, and Java backend logic.

📁 Project Structure
text
/pg-life
  /src
    /model              # Java Beans and Data Access Objects (DAOs)
    /controller         # Servlet logic, authentication, and session management
    /view               # JSP pages or frontend HTML/CSS
    /util               # Utility classes (DB connection, helpers)
  /sql                  # SQL scripts to set up required tables
  /assets               # Images, logos, and static files
  README.md
🛠️ Technologies Used
Java (Servlets/JSP or Spring Boot)

MySQL (or another RDBMS)

HTML, CSS & Bootstrap (for UI)

JDBC (for database connectivity)

Tomcat or compatible Java Servlet container

🚀 Getting Started
Prerequisites
JDK 8 or higher

MySQL database server

Maven or Gradle (optional, for dependency management)

Apache Tomcat or Spring Boot (for running webapp)

Setup Steps
Clone the Repository:

bash
git clone (https://aman18raj.github.io/PGLife-/)
cd pg-life
Configure Database:

Import /sql/pg_life_schema.sql into MySQL.

Edit src/util/DBConnection.java with your database credentials.

Build and Run:

For Servlet/JSP:

Compile using your IDE or javac.

Deploy on Tomcat and access via browser at localhost:8080/pg-life.

For Spring Boot:

./mvnw spring-boot:run

Access via browser at localhost:8080/.

✨ Features
Student and Owner registration/login

Search PGs by city/area

Filter and sort PG search results

PG listing details (with image gallery & amenities)

Booking and booking history

Owner dashboard (post/view/manage PGs)

Responsive frontend using Bootstrap

📂 Example Database Schema
users: Stores student and owner profiles

pg_listings: PG accommodation details

bookings: Stores booking and reservation records

amenities: Facilities available per PG

Detailed PG Pages: Expand on photos, facilities, rules, and user reviews.

Login & Registration Pages: Ready-to-integrate user auth front-end templates.
