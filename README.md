# Employee Management System

A web-based Employee Management System developed using **ASP.NET Core MVC** and **Entity Framework Core**. The application provides basic employee management operations with data stored in a SQL Server database.

## Features

* Add a new employee
* View all employees
* View employee details
* Edit employee information
* Delete employee records
* SQL Server database integration
* Entity Framework Core migrations
* Model validation
* Responsive web interface

## Technologies Used

* **C#**
* **ASP.NET Core MVC**
* **Entity Framework Core**
* **SQL Server**
* **HTML**
* **CSS**
* **Bootstrap**
* **Razor Views**
* **Git & GitHub**

## Project Structure

```text
EmployeeManagementSystem
?
??? Controllers
?   ??? EmployeesController.cs
?   ??? HomeController.cs
?
??? Data
?   ??? ApplicationDbContext.cs
?
??? Migrations
?
??? Models
?   ??? Employee.cs
?   ??? ErrorViewModel.cs
?
??? Views
?   ??? Employees
?   ??? Home
?   ??? Shared
?
??? wwwroot
?   ??? css
?   ??? js
?   ??? lib
?
??? Program.cs
??? appsettings.json
??? EmployeeManagementSystem.csproj
```

## Employee Operations

The system follows the basic **CRUD** operations:

| Operation | Description                 |
| --------- | --------------------------- |
| Create    | Add a new employee          |
| Read      | View employee records       |
| Update    | Modify employee information |
| Delete    | Remove an employee          |

## Database

The application uses **SQL Server** as the database and **Entity Framework Core** for database interaction.

The `Employee` entity contains information such as:

* Employee ID
* Name
* Department
* Salary

Entity Framework Core migrations are used to create and update the database schema.

## How to Run the Project

### 1. Clone the repository

```bash
git clone https://github.com/magisankar58-lgt/Employee-Management-System.git
```

### 2. Open the project

Open the `.csproj` file in **Visual Studio**.

### 3. Configure the database

Update the SQL Server connection string in:

```text
appsettings.json
```

### 4. Apply migrations

Run:

```bash
dotnet ef database update
```

### 5. Run the application

Run the project from Visual Studio or use:

```bash
dotnet run
```

## Learning Outcomes

Through this project, I gained practical experience in:

* ASP.NET Core MVC architecture
* C# programming
* Entity Framework Core
* CRUD operations
* SQL Server database integration
* MVC Controllers and Razor Views
* Database migrations
* Git and GitHub version control

## Future Enhancements

* User authentication and authorization
* Employee search and filtering
* Pagination
* Department management
* RESTful Web API
* React frontend integration

## Author

**Magi S**

B.E. Electronics and Communication Engineering
