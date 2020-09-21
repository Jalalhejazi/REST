## About REST API


Search for: dotnet core web api

- https://docs.microsoft.com/en-us/aspnet/core/?view=aspnetcore-3.1
- https://docs.microsoft.com/en-us/aspnet/core/tutorials/first-web-api?view=aspnetcore-3.1&tabs=visual-studio



## Tools

- https://code.visualstudio.com/
- https://github.com/tulios/json-viewer
- google chrome



## First Web API project

```PowerShell

scoop install dotnet-sdk
dotnet --version 
# expecting version 3.1.x

dotnet new webapi -o TodoApi
cd TodoApi
dotnet add package Microsoft.EntityFrameworkCore.SqlServer
dotnet add package Microsoft.EntityFrameworkCore.InMemory
code .

```
