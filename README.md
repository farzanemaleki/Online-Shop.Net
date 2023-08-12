# Online-Shop.Net

create Solution
```bash
    dontnet new sln -o OnlineShop
```
create API, Core, Infrastructure Layers
 ```bash
    dotnet new webapi -o API
    dotnet new classlib -o Core
    dotnet new classlib -o Infrastructure
```  
add layers to solution for example for API layer
```bash
    dotnet sln add API/API.csproj 
```

