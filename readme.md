You are reading README.md (markdown)

# REST API using dotnet core (3.1)

- use dotnet 3 or 5
- ~~DO NOT USE dotnet 4.x~~




## The-future-of-net-standard
- https://devblogs.microsoft.com/dotnet/the-future-of-net-standard/



## About REST API

Search for: dotnet core web api

- https://docs.microsoft.com/en-us/aspnet/core/?view=aspnetcore-3.1
- https://docs.microsoft.com/en-us/aspnet/core/tutorials/first-web-api?view=aspnetcore-3.1&tabs=visual-studio

## Moderne MicroServices Architecture

- https://dotnet.microsoft.com/download/e-book/microservices-architecture/pdf



## Tools

- https://code.visualstudio.com/
- https://scoop.sh/
- https://docs.servicestack.net/netcore


## Ready WebAPI with Security built-in
- https://github.com/Jalalhejazi/JwtAuthDemo

```powershell
git clone https://github.com/Jalalhejazi/JwtAuthDemo.git
cd JwtAuthDemo
docker-compose up --build --remove-orphans

```


## Ready WebAPI with SQLSERVER Connection and Azure DevOps

```powershell
git clone https://dev.azure.com/superusers-kursus/Webapp-snippets
cd Webapp-snippets
code .
dotnet build
dotnet run
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

# How to run with default ports http://localhost:5000 and https://localhost:5001
dotnet run

# How to run and listen to any availabe free ports on http and https
dotnet run --urls "http://[::1]:0;https://[::1]:0"

```

## Open new terminal and test API 

- https://localhost:5001/WeatherForecast
- https://localhost:PORT/WeatherForecast



## Configuration 

- [dotnet core ConnectionString](https://www.google.com/search?q=dotnet+core+connectionstring)







