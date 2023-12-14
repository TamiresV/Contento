<h1 aligh="center">Contento</h1>

## 💻 Projeto
Contento é um site onde os usuários podem fazer avaliações, deixando notas e comentários, sobre filmes e livros.

O projeto surgiu através do vídeo da Attekita sobre [ideias de projetos](https://www.youtube.com/watch?v=z2kNoS8jfMg).

Apesar do site [The Movie Database](https://www.themoviedb.org/) fornecer informações de filmes através de uma api, neste projeto será criada uma api própria, usando o site como referência.

## 🔖 Layout

## 🛠️ Tecnologias e Ferramentas

- C#
- .Net
- SQL
- Entity Framework Core
- Angular
- Design Patterns

## :page_facing_up: Migrations
Para executar as migrations é necessário ter o [entity framework core](https://learn.microsoft.com/en-us/ef/core/get-started/overview/install) instalado. Para instalá-lo de forma global execute o comando abaixo no prompt

`dotnet tool install --global dotnet -ef`

Para criar uma migration execute `dotnet ef migrations add <NomeDaMigration>`

Para aplicar a migration no banco de dados execute `dotnet ef database update`
