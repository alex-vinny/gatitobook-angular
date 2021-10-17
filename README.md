# Gatitobook

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 12.2.10.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via a platform of your choice. To use this command, you need to first add a package that implements end-to-end testing capabilities.

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.io/cli) page.

### CSS
> `npm install bootstrap font-awesome`

edit angular.json e colocar o caminho do css do projeto
"./node_modules/bootstrap/dist/css/bootstrap.min.css",
"./node_modules/font-awesome/css/font-awesome.css"

criar o nosso primeiro módulo
-d não executa, apenas mostra
`ng generate module home --routing -d`

pra que serve um módulo
organização de projetos
tipos: módulo de funcionalidade

criar o componente:
ng generate component home

css é isolado a nível de componente


home.component.ts -> comportamentos do componente
arquivo spec é o arquivo de teste

arquivos estáticos em projeto angular
atríbuto assets do arquivo angular.json

trabalhar nas rotas usando lazy-load
usar via rota pela tag router-outlet
carregamento sobre demanda, somente quando o usuário solicitar a rota

criar componente dentro de um módulo existente:
ng generate component home/login

criação de módulo de autenticação
ng generate module autenticacao

criar os serviços para um módulo especifíco
ng generate service autenticacao/autenticacao

formulários do tipo template para receber e enviar dados

[()] -> comunicação de duas vias entre a classe e o template
Observable é um objeto da biblioteca RjxJs não é do angular, mas muito consumido pelo angular
