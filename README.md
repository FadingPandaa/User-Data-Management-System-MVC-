## 📖 Project Overview

This project is an ASP.NET MVC web application that demonstrates how to 
connect to a SQL Server database and execute basic SQL queries.

It focuses on creating a database table and storing user input (name and age) through a web form.

Key concepts:

- Database connectivity using ADO.NET
- SQL query execution (CREATE TABLE, INSERT)
- HTTP GET and POST methods
- Form handling in MVC
- Data flow between models, controllers, and views

------------------
## 🚀 Features

✅ Automatic table creation on page load

✅ User data submission via HTTP POST

✅ SQL Server database integration

✅ Data storage using INSERT queries

✅ MVC structured design

------------------------
## 🛠️ Technologies Used

* C#
* ASP.NET MVC
* ADO.NET (SqlConnection & SqlCommand)
* SQL Server (LocalDB)
* Razor Views
* HTML5 & CSS3
* Visual Studio

-----------------
## ▶️ How to Run

Using Visual Studio:

1. Open the solution file
2. Ensure SQL Server LocalDB is installed
3. Build the project
4. Click Run (IIS Express)

Use .NET CLI: dotnet build, 
              dotnet run
                  
-------------------
## 🔄 How It Works

1. User accesses the home page via HTTP GET
2. The application automatically attempts to create a users table
3. A form is displayed to collect user input (name and age)
4. User submits the form via HTTP POST
5. The controller validates the input
6. Data is inserted into the database using SQL queries
7. The page reloads with submitted data

--------------------
## ⚠️ Limitations

- Table creation runs every time the page loads (may cause errors if table already exists)
- No advanced error handling or logging
- No input validation beyond basic model validation
- Hardcoded connection string
- No data retrieval/display from database

---------------------
## 📈 Future Improvements

* Add check to prevent duplicate table creation
* Implement full CRUD operations (Create, Read, Update, Delete)
* Use Entity Framework instead of raw SQL
* Improve validation and error handling
* Move connection string to configuration securely
* Display stored users in the UI
* Enhance UI/UX design

-------------------------
## 👨‍💻Author: 
Keabetswe Masole

Software Used: <br> 
Visual Studio 2022
