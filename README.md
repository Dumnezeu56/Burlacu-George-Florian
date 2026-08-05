````markdown
# 🎬 MovieHub

MovieHub is a Java desktop application designed for managing a personal movie collection through an intuitive graphical interface. The application allows users to organize, search and manage movie information while storing all data in a relational MariaDB database.

The project was developed to demonstrate object-oriented programming principles, database integration and desktop application development using Java.

---

## Features

### Movie Management

- Add new movies
- Edit existing movie information
- Delete movies
- View complete movie details
- Search movies
- Browse the entire collection

### Database Integration

- Persistent data storage
- Relational database design
- Fast data retrieval
- SQL-based operations
- Reliable data management

### Desktop Application

- User-friendly graphical interface
- Interactive forms
- Real-time data updates
- Input validation
- Easy navigation

---

## Technology Stack

| Technology | Purpose |
|------------|---------|
| Java | Core application |
| Java Swing | Desktop graphical interface |
| MariaDB | Relational database |
| SQL | Data manipulation |
| JDBC | Database connectivity |
| Maven | Dependency management |

---

## Project Architecture

The application follows a layered architecture that separates the graphical interface from the database layer.

```
                +----------------------+
                |      Java Swing      |
                |         GUI          |
                +----------+-----------+
                           |
                    User Actions
                           |
                +----------v-----------+
                |    Business Logic    |
                +----------+-----------+
                           |
                      JDBC Driver
                           |
                +----------v-----------+
                |      MariaDB         |
                |      Database        |
                +----------------------+
```

This structure improves maintainability and simplifies future development.

---

## Database

MovieHub stores all information inside a relational MariaDB database.

Typical information stored includes:

- Movie title
- Genre
- Release year
- Rating
- Duration
- Description
- Additional movie metadata

The database design allows efficient CRUD operations while maintaining data consistency.

---

## Core Functionalities

### Create

Add new movies to the database.

### Read

Display all stored movies and view detailed information.

### Update

Modify movie information whenever necessary.

### Delete

Remove movies from the collection.

### Search

Find movies quickly using search functionality.

---

## Project Structure

```
MovieHub
│
├── src/
│   ├── main/
│   │   ├── java/
│   │   └── resources/
│
├── database/
├── pom.xml
└── README.md
```

---

## Installation

### Requirements

- Java JDK 17 or newer
- Maven
- MariaDB

---

### Clone Repository

```bash
git clone https://github.com/GeorgeB313/MovieHub.git
```

---

### Build

```bash
mvn clean package
```

---

### Run

```bash
mvn exec:java
```

or execute the generated JAR file.

---

## Database Configuration

Configure your MariaDB connection before running the application.

Example:

- Database name
- Username
- Password
- JDBC connection URL

Update these values according to your local environment.

---

## Skills Demonstrated

This project demonstrates practical experience with:

- Object-Oriented Programming
- Java Desktop Development
- Java Swing
- SQL
- MariaDB
- JDBC
- CRUD Operations
- Relational Database Design
- Software Architecture
- Input Validation
- Data Persistence
- Maven Build System

---

## Future Improvements

Potential future enhancements include:

- User authentication
- Movie posters
- Watchlist management
- Favorites section
- Advanced filtering
- Multiple user accounts
- Statistics dashboard
- Export and import functionality
- Cloud database support
- REST API integration

---

## Learning Outcomes

During the development of this project, the following concepts were applied:

- Database normalization
- Java object-oriented programming
- GUI development
- SQL query implementation
- Data validation
- Exception handling
- Layered application architecture

---

## Author

**George-Florian Burlacu**

GitHub

https://github.com/GeorgeB313

---

Developed as a university database and Java programming project.
````
