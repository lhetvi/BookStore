# BookStore
The BookStore Web Application is a C# web application developed by Hetvi Ladani & Srushti Gol. This Web Application allows the users to manage and categorise various types of books available in a book store. This README provides an overview of the project and instructions for setting it up.

## Project Purpose
The purpose is to provide an efficient and user-friendly platform for effective management of the books based on their genre, author and publisher. With its intutive interface and smooth functionality, the user can view, add, delete and modify the genre list, author list, publisher list and the book list.This web Application also provides a feture of User authentication and authorization.

## Technologies Used
- C# (Programming language)
- ASP.NET Core (Web framework)
- Entity Framework Core (Object-relational mapping)
- MS SQL Server (Database)
- Razor Pages (View engine)
- Identity Framework (User authentication)

## Getting Started
These instructions will help you get a copy of the project up and running on your local machine.

### Prerequisites
Visual Studio (2019 or later)
.NET Core SDK (3.1 or later)
MS SQL Server (Express or higher)

### Installation
1. Clone the repository to your local machine using Git:
```bash git clone https://github.com/lhetvi/BookStore.git
2. Open the project in Visual Studio.
3. Configure the connection string for the database in the appsettings.json file:
```bash
"ConnectionStrings": {
    "DefaultConnection": "Server=YOUR_SERVER;Database=BookStore;User Id=YOUR_USERNAME;Password=YOUR_PASSWORD;"
}
4. Open the Package Manager Console in Visual Studio and run the commands to apply migrations and create the database.
5. Build and run the project in Visual Studio.
