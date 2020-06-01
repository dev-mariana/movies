# Curso Intermediário de Angular 8 - Intermediate Course of Angular 8

Este projeto foi gerado com o Angular CLI e foi criado no curso da Digital Innovation One.
Código base criado por Renan Rafael Bertoldo.

Este projeto foi criado para gerenciar um sistema de filmes, onde é possível ver a listagem de filmes, editar, cadastrar novos filmes e excluir.

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) and was created in the course of Digital Innovation One.

This project was created to manage a system of movies, where is possible you view the list of movies, edit, registered new movies and delete them.

![](https://github.com/dev-mariana/movies/blob/master/src/assets/images/filmes.PNG)

## Instalação - Installation

1. clone o repositório `git clone git@github.com:dev-mariana/movies.git`.
2. Entre no projeto e instale as dependencias `npm install`.

Use git clone in the repository `git clone git@github.com:dev-mariana/movies.git`.
Access the folder of project and install the dependencies `npm install`.

## Ambiente Local - Development Server

Use ng serve para rodar a aplicação no localhost: `http://localhost:4200/`. O projeto já está com reload automático conforme as alterações que você realizar no código.

Run ng serve for a development server, navigate to http://localhost:4200/. The app will automatically reload if you change any of the source files.

## Simulando o Backend - Simullating the Backend

Execute `npm install -g json-server` para instalar globalmente o servidor json. Após a instalação entre na pasta servers do projeto e execute `json-server --watch db.json`, com isso um servidor será inicializado na url `http://localhost:3000/`, após a inicialização sera possível realizar requisições http.

Run `npm install -g json-server` to install globally. After, access the project's servers folder and run `json-server --watch db.json` for the server to be initialized at the url http://localhost:3000/, after initialization it will be possible to make http requests.

## Build

Execute `ng build` para gerar o compilado do projeto. O projeto vai ser criado dentro do diretório `dist/`. Adicionar `--prod` junto comando de build para gerar minificado e pronto para o ambiente de produção.

Run ng build to build the project. The build artifacts will be stored in the dist/ directory. Use the --prod flag for a production build.

## Running unit tests

Run ng test to execute the unit tests via Karma.

## Running end-to-end tests

Run ng e2e to execute the end-to-end tests via Protractor.

# Further help

To get more help on the Angular CLI use ng help or go check out the Angular [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).
