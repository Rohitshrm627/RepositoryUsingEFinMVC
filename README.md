# Repository Using EF in MVC
Repository pattern Using EF in MVC

## What is the Repository Design Pattern in C#?
The Repository Pattern in C# is used to create an abstraction layer between the data access layer and the business logic layer of the application. That abstraction layer is generally called the Repository Layer and it will directly communicate with the data access layer, gets the data and provides it to the business logic layer. 
The main advantage to use the repository design pattern is to isolate the data access logic and business logic. So that if we do any changes in any of this logic, then that should affect other logic. So let us discuss the step by step procedure to implement the repository pattern in C#.

## Why we need the Repository Pattern in C#?
As we know, nowadays, most of the data-driven applications need to access the data residing in one or more other data sources. Most of the time data sources will be a database. Again, these data-driven applications need to have a good and secure strategy for data access to perform the CRUD operations against the underlying database. One of the most important aspects of this strategy is the separation between the actual database, queries and other data access logic from the rest of the application. In our example, we need to separate the data access logic from the Employee Controller. The Repository Design Pattern is one of the most popular design patterns to achieve such separation between the actual database, queries and other data access logic from the rest of the application.

### Above Application is developed using EF and below are the steps.
1. Create the Required Database tables
2. Create a new ASP.NET MVC application
3. Adding ADO.NET Entity Data Model
4. Creating Employee Repository
5. Use Employee Repository in a Controller
6. Run the application


learning some application architectures and design patterns.
