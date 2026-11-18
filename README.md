## Visitor Management System

## About the Project
The Visitor Management System is a Java-based desktop application developed to manage visitor information efficiently. It helps organizations register visitors, track their entry and exit times, search visitor records, and monitor visitor activities through a dashboard.

## Technologies Used
- Java
- JavaFX
- MySQL
- JDBC
- Maven
- CSS

## Features
- Dashboard with visitor statistics
- Register new visitors
- View all visitor records
- Search visitors by ID, name, or phone number
- Check out visitors
- Automatically record entry and exit times
- Calculate total visit duration
- Track visitors currently inside

## Database
The project uses MySQL to store visitor information.

Database Name: `visitor_management`

To create the database, execute the `database.sql` file in MySQL Workbench.

## How to Run
1. Clone or download this repository.
2. Open the project in VS Code or IntelliJ IDEA.
3. Make sure Java and Maven are installed.
4. Set up MySQL and execute `database.sql`.
5. Configure your database connection details.
6. Run the application using:

```bash
mvn javafx:run
```

## Project Structure
- `dao` – Database operations
- `database` – Database connection
- `model` – Visitor data model
- `service` – Business logic
- `ui` – User interface
- `resources` – Application styles

## Purpose
The main objective of this project is to simplify visitor record management and improve the efficiency of entry and exit tracking.

## Author
Sathish Kumar S
