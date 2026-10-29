# Books Management System

A web application built with **ASP.NET Core Razor Pages** and **SQL Server LocalDB** for managing a library database.

## 📌 Project Overview
This university project implements a complete CRUD (Create, Read, Update, Delete) web application that manages book records in a database.

## 🛠️ Tech Stack & Prerequisites
- **Framework:** ASP.NET Core Razor Pages (.NET Core)
- **Database:** SQL Server LocalDB (`(localdb)\MSSQLLocalDB`)
- **IDE:** Visual Studio 2026 Community Edition
- **UI:** Bootstrap 5

## 📁 Project Structure
- `Pages/Books/`
  - `Index.cshtml` - Displays the list of books from the database.
  - `Create.cshtml` - Form to add a new book record.
  - `Edit.cshtml` - Form to update existing book details.
  - `Delete.cshtml` - Confirmation page to remove a book record.
- `appsettings.json` - Database connection configuration.

## 🚀 How to Run the Project
1. **Clone or Download** this repository.
2. Open `Books_Management_System.sln` in **Visual Studio**.
3. Ensure **SQL Server Express LocalDB** is installed and running on your machine.
4. Verify the connection string in `appsettings.json` points to your LocalDB instance:
   ```json
   "ConnectionStrings": {
     "DefaultConnection": "Server=(localdb)\\MSSQLLocalDB;Database=BMS_DB1;Trusted_Connection=True;MultipleActiveResultSets=true;TrustServerCertificate=True"
   }
