<h1 aligh="center">Contento</h1>

## 💻 Project
Contento is a site where users can to assess, leaving notes and comments about movies and books. 

The project borned because the video from Attekita about [project ideas](https://www.youtube.com/watch?v=z2kNoS8jfMg).

Although the site [The Movie Database](https://www.themoviedb.org/) supply informations about movies through a api, in this project will be created a own api, using the site as reference.

## 🔖 Layout

## 🛠️ Tecnologies and Tools

- C#
- .Net
- SQL
- Entity Framework Core
- Angular
- Design Patterns

## :page_facing_up: Migrations
To execute the migrations is necessary install the [entity framework core](https://learn.microsoft.com/en-us/ef/core/get-started/overview/install). To install globally execute the command below in your prompt:

`dotnet tool install --global dotnet -ef`

To criate a migration execute `dotnet ef migrations add <NomeDaMigration>`

To apply the migration in the database execute `dotnet ef database update`