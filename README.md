# Blazor Application
This is a Blazor web app building with ASP.NET on Linux.

ASP is a server-side scripting technology used to create dynamic and interactive web pages. 

.NET is a software development framework that is designed to provide an environment for building and running applications and supports multiple programming languages, such as C#.

# ContosoPizzaWebAPI RESTful web API

The ContosoPizzaWebAPI directory contains a RESTful web API project built with ASP.NET Core. This project is designed to serve as the backend for the Blazor application, providing a way to handle HTTP requests for data operations. The main purpose of this web API is to demonstrate the creation, reading, updating, and deleting (CRUD) operations on a simulated database, showcasing essential backend functionalities. It is designed to work in conjunction with the Blazor frontend, providing a full-stack development experience.

# How it works
First to create the app you must run the command 'dotnet new blazor -o BlazorApp' on the terminal. This will create a directory and it's content.

To build and start the app you must run the command 'dotnet watch' on the terminal. It will begin listening http://localhost:<port number> and then open a browser and navigate to that address.

The page will display the Home.razor file located under the Components/Page directory along with it's contents.

# Resources
https://dotnet.microsoft.com/en-us/learn/aspnet/blazor-tutorial/create
