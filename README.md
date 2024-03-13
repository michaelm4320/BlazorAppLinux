# Blazor Application
This is a full-stack Blazor web appplication with ASP.NET on Linux.

Blazor is part of the ASP.NET Core web app framework used to build interactive web UIs using C# instead of JavaScript.
* The Front-end is the Blazor application that utilizes Razor components that allows the users to see and interact with their web browsers.
* The back end is the ASP.NET Core Web API and it will be responsible in handling requests from the front end and sends back requests data.

.NET is a software development framework that is designed to provide an environment for building and running applications and supports multiple programming languages, such as C#.

ASP.NET is a subset of .NET, specifally designed for web development. It runs on the .NET framework with all it's features, but adds libraries and tools specifically for building web applications.


# ContosoPizzaWebAPI RESTful web API

The ContosoPizzaWebAPI directory contains a RESTful web API project built with ASP.NET Core. This project is designed to serve as the backend for the Blazor application, providing a way to handle HTTP requests for data operations. The main purpose of this web API is to demonstrate the creation, reading, updating, and deleting (CRUD) operations on a simulated database, showcasing essential backend functionalities. It is designed to work in conjunction with the Blazor frontend, providing a full-stack development experience.

The 'dotnet run' command is used to run the web server which in turn have the web server listen to a specific port (my local machine using localhost). My browser will send a GET request and respond with the web page I requested.

# General terms

An API sends and requests data that allows two applications to talk to each other.

A RESTful API is a subset of an API that uses HTTP methods to send and request data using GET, POST, PUT, and DELETE.
* GET retrieves existing data
* POST creates new data
* PUT updates or changes data
* DELETE removes data

# How it works
First to create the app you must run the command 'dotnet new blazor -o BlazorApp' on the terminal. This will create a directory and it's content.

To build and start the app you must run the command 'dotnet watch' on the terminal. It will begin listening to http://localhost:(port number) and then open a browser and navigate to that address. This command is userful for developers as it automatically recompiles and restarts your application when changes are detected without having to manually stop and start the server every time you change your code.

The page will display the Home.razor file located under the Components/Page directory along with it's contents.

# Resources
https://dotnet.microsoft.com/en-us/learn/aspnet/blazor-tutorial/create
