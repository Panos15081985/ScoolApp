# SchoolApp

SchoolApp is a backend application built with C# and .NET, providing basic CRUD operations for managing courses, students, teachers, and users. It uses Microsoft SQL Server Management Studio (MSSMS) as its database and follows a **Model-First** approach with Entity Framework.

## Features

- CRUD operations for **Courses**, **Students**, **Teachers**, and **Users**.
- Many-to-many relationship management between students and courses.
- Entity Framework migrations for database management.
- Swagger UI for API documentation and testing.

## Database Schema

The application includes the following tables:

- `Courses`
- `Students`
- `Teachers`
- `Users`
- `StudentsCourses` (many-to-many relation)
- `EFMigrationHistory`

##The application will start and expose Swagger UI at:
http://localhost:5000/swagger
