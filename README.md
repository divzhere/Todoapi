# Todo App API using ASP.NET Core 3.1

A web API that can manage "to-do" items stored in a database made using [ASP.Net Core 3.1](https://docs.microsoft.com/en-us/aspnet/core/?view=aspnetcore-3.1)

## API Endpoints

|API   |Description   |Request Body   |Response Body 
|---|---|---|---|
|GET /api/TodoItems|Get all Todo Items  | none  |Array of todo items|
|GET /api/TodoItems/{id}|Get an item by ID   |none|To-do item   
|POST /api/TodoItems |Add a new Item   |To do item |To-do item
|PUT /api/TodoItems/{id} |Update an existing item|To do item|None
|DELETE /api/TodoItems/{id} |Delete an Item|None|None   

## Running the Project

Following command can be used to run the project
```sh
dotnet run
```

This project can also be run from [Visual Studio IDE](https://visualstudio.microsoft.com/) or [Visual Studio Code](https://code.visualstudio.com/)


