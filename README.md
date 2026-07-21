# NorthwindConnectedModelWPF

A WPF desktop application built with C# and ADO.NET's **connected model** approach, 
demonstrating direct database access using `SqlConnection`, `SqlCommand`, and `SqlDataReader`/`DataAdapter` 
against the Northwind database's Employees table.

## Features

- **Load Grid** – Retrieves and displays all employee records (EmployeeID, FirstName, LastName, City, Country) in a DataGrid
- **Search Emp by Name** – Filters employees by first and/or last name
- **Count Table Rows** – Displays the total number of rows in the Employees table
- **Insert New Emp** – Adds a new employee record using the First Name / Last Name input fields

## Tech Stack

- C# / .NET
- WPF (Windows Presentation Foundation)
- ADO.NET (Connected Model)
- SQL Server (LocalDB) – Northwind database

## Getting Started

### Prerequisites
- Visual Studio 2026 
- SQL Server LocalDB
- Northwind sample database

### Setup
1. Clone this repository
2. Restore the Northwind database to your local SQL Server / LocalDB instance
3. Update the connection string in `App.config` if your database name or server differs:
```xml
   <connectionStrings>
     <add name="Northwind"
          connectionString="Server=(LocalDB)\MSSQLLocalDB;Database=Northwind;Trusted_Connection=True;"
          providerName="Microsoft.Data.SqlClient" />
   </connectionStrings>
```
4. Build and run the project in Visual Studio

## Screenshots
<img width="1262" height="697" alt="image" src="https://github.com/user-attachments/assets/67701ddb-10c2-4b1b-9159-09d3026a93ca" />


## Author

Created as part of coursework for my labs  **.NET Technologies Using C#** – Sheridan College
