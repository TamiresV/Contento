<h1 aligh="center">Contento API</h1>

## 🛠️ Swagger
To access the swagger is necessary add `/swagger` in the url

## :page_facing_up: Migrations
To execute the migrations is necessary install the [entity framework core](https://learn.microsoft.com/en-us/ef/core/get-started/overview/install). 

To install globally execute the command below in your prompt:

`dotnet tool install --global dotnet-ef`

To criate a migration execute `dotnet ef migrations add <NomeDaMigration>`

To apply the migration in the database execute `dotnet ef database update`