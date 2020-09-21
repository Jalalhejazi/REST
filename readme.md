## About REST API


Search for: dotnet core web api

- https://docs.microsoft.com/en-us/aspnet/core/?view=aspnetcore-3.1
- https://docs.microsoft.com/en-us/aspnet/core/tutorials/first-web-api?view=aspnetcore-3.1&tabs=visual-studio



## Tools

- https://code.visualstudio.com/
- https://github.com/tulios/json-viewer
- google chrome
- https://scoop.sh/


## Ready WebAPI with Security built-in
- https://github.com/Jalalhejazi/JwtAuthDemo

```powershell
git clone https://github.com/Jalalhejazi/JwtAuthDemo.git
cd JwtAuthDemo
#code readme.md

```



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

# How to build
dotnet build

# How to run any use default ports http://localhost:5000 and https://localhost:5001
dotnet run

# How to run and listen to any availabe free ports on http and https
dotnet run --urls "http://[::1]:0;https://[::1]:0"

```

## Open new terminal and test API 

- https://localhost:5001/WeatherForecast
- https://localhost:PORT/WeatherForecast



