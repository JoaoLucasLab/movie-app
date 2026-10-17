# Movie Library MVC Application

This project is an ASP.NET Core MVC movie library. It uses Entity Framework Core and SQLite to store movie records and provides pages for viewing, searching, filtering, creating, editing, viewing details, and deleting movies. The database is seeded with sample movies when the application starts.

## Instructions for Build and Use

Steps to build and/or run the software:

1. Open a terminal in the project directory.
2. Restore the project dependencies and build the application with `dotnet restore` and `dotnet build`.
3. Run the application with `dotnet run`, then open the HTTPS URL shown in the terminal.

Instructions for using the software:

1. Open the Movies page to view the seeded movie library.
2. Use the Genre, Release year, and Title fields to filter the movie list, or select **Add movie** to create a new movie.
3. Use **View**, **Edit**, or **Delete** beside a movie to manage its information.

## Development Environment

To recreate the development environment, you need the following software and/or libraries with the specified versions:

* .NET 10 SDK, because the project targets `net10.0`.
* ASP.NET Core MVC.
* Entity Framework Core 10.0.12 with the SQLite provider, plus the EF Core Design and Tools packages.

## Useful Websites to Learn More

I found these websites useful in developing this software:

* [ASP.NET Core MVC overview](https://learn.microsoft.com/aspnet/core/mvc/overview)
* [Microsoft tutorial: Get started with ASP.NET Core MVC](https://learn.microsoft.com/aspnet/core/tutorials/first-mvc-app/start-mvc)
* [Microsoft tutorial: Add a model to an ASP.NET Core MVC app](https://learn.microsoft.com/aspnet/core/tutorials/first-mvc-app/adding-model)

## Future Work

The following items I plan to fix, improve, and/or add to this project in the future:

* [ ] Add authentication and authorization so only approved users can change the library.
* [ ] Add more advanced sorting, pagination, and movie metadata such as posters and descriptions.
