# Projeto Biblioteca - Programação Web

Este projeto é um sistema de biblioteca desenvolvido para a disciplina de Programação Web. Ele permite visualizar livros e informações sobre autores de forma simples e organizada.

## Requisitos

* .NET SDK 10.0
* MySQL (Workbench ou outro)
* Entity Framework Core Tools

## Tecnologias Utilizadas

* C# com ASP.NET Core MVC
* MySQL
* Bootstrap
* Entity Framework Core

## Como executar o projeto

### 1. Clonar o repositório

```bash
git clone https://github.com/mariaclarakim/BIBLIOTECAPWEB.git
cd BIBLIOTECAPWEB
```

### 2. Configurar o banco de dados

No arquivo `appsettings.json`, coloque seu usuário e senha do MySQL:

```json
"ConnectionStrings": {
  "DefaultConnection": "Server=localhost;Database=biblioteca_db;User=seu_usuario;Password=sua_senha;"
}
```

### 3. Criar o banco de dados

Execute o comando:

```bash
dotnet ef database update
```

### 4. Rodar o projeto

```bash
dotnet run
```

## Organização do projeto

* **Controllers**: controlam o funcionamento das páginas
* **Models**: representam os dados (Livro e Autor)
* **Views**: páginas que o usuário vê
* **wwwroot**: arquivos de estilo e scripts

## Funcionalidades

* Lista de livros na página inicial
* Visualização de autores
* Exibição das obras de cada autor
* Layout adaptado para celular e computador

## Autoras

* Maria Clara Braga
* Laís Alves

