Projeto Biblioteca - Programação Web

Este é um projeto de sistema de biblioteca desenvolvido para a disciplina de Programação Web. O objetivo é gerenciar um acervo de livros e informações sobre autores, usando tecnologias modernas de desenvolvimento web.

O que é necessário para rodar o projeto

.NET SDK 10 

Servidor MySQl (workbench)

Entity Framework Core Tools instalado no terminal

Tecnologias que usamos

C# com ASP.NET Core MVC: Para a lógica e estrutura do site.

MySQL: Para salvar os dados dos livros e autores.

Bootstrap: Para deixar o visual bonito e funcionando bem.

Entity Framework: Para fazer a conexão entre o código e o banco de dados.

Como configurar na sua máquina

Baixar o projeto:
Abra o terminal e use os comandos abaixo para clonar o repositório:

git clone [https://github.com/mariaclarakim/BIBLIOTECAPWEB.git](https://github.com/mariaclarakim/BIBLIOTECAPWEB.git)
cd BIBLIOTECAPWEB


Configurar o banco de dados:
No arquivo appsettings.json, você precisa colocar o seu usuário e a sua senha do MySQL:

"ConnectionStrings": {
  "DefaultConnection": "Server=localhost;Database=biblioteca_db;User=seu_usuario;Password=sua_senha;"
}


Criar as tabelas automaticamente:
Rode este comando para o Entity Framework criar o banco e as tabelas no seu MySQL:

dotnet ef database update


Rodar o site:

dotnet run


Organização das pastas

Controllers: Onde controlamos o que acontece em cada página.

Models: Onde definimos como são os objetos Livro e Autor.

Views: As páginas HTML do site que o usuário vê.

wwwroot: Pasta com os arquivos de estilo (CSS) e scripts.

O que o sistema faz

Lista todos os livros cadastrados na tela inicial.

Permite clicar no nome de um autor para ver a biografia dele.

Mostra quais livros pertencem a cada autor específico.

Visual que se adapta a tablets e celulares.

Autoras

Maria Clara Braga

Laís Alves 
