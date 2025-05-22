# TodoList

## Conhecendo os arquivos:
**Angular.json:** Arquivo que contém uma série de configurações do app angular do nosso projeto, como otimização de código, configuração do build etc..

**Package Lock e Package.json:** arquivos específicos do node com as dependências e scripts.
**tsconfig:** arquivo de configuração do typescript.

## Códigos Fonte:
**styles.css:** Estilização global.
**main.ts:** Dá o pontapé inicial da aplicação angular.
**index.html:** Arquivo que é renderizado na página inicial, invoca o app root.

**Pasta App:** Contém os componentes da aplicação.
**app.component.specs:** Arquivo para testes unitários.
**app.config.ts:** Arquivo de configuração que diz pro angular como ele vai renderizar os componentes.

## Criando Componentes:
No angular as aplicações são construídas em torno de componentes, que são os blocos de construção fundamentais. Cada componente contém três partes:
Classe TypeScript: Escrito em typescripts providencia o espaço para construir a lógica da aplicação.
HTML Template: Definimos a interface de usuário para o componeO que é Angular?
É um framework utilizado por desenvolvedores na construção de sites dinâmicos e aplicativos web interativos mantido pela equipe do Google.


**Detalhe do projeto:**
Neste tutorial iremos criar uma lista de tarefas.


**Pré requisito:**
Antes de tudo é necessário instalar o node.js na máquina (e caso esteja usando o vscode recomendo instalar a extensão do angular).


**Criando um novo projeto:**
Após a instalação do node o próximo passo é fazer a instalação do angular no projeto pelo terminal, usando o comando: npm install -g @angular/cli.
Para verificar se a instalação deu certo basta escrever ng version no terminal.


Instalado, agora temos que criar o projeto utilizando o comando: ng new <project-name> fique a vontade para escrever o nome que achar melhor.


O cli do angular iniciará algumas perguntas a primeira sendo qual o formato de stylesheet você gostaria de utilizar, neste projeto utilizaremos o css padrão
A próxima pergunta é se gostaria de habilitar SSR e SSG, digite n no terminal e confirme.
nte. Nós podemos escrever isso diretamente na classe do componente se for um template pequeno, ou para templates mais complexos, podemos incluí-los em seu próprio arquivo HTML.
CSS Styles: Os estilos que escrevemos para nossos componentes são escopados para eles, de forma similar ao template do componente. Os estilos podem ser incluídos inline dentro da classe do componente ou escritos em seu próprio arquivo separado. Neste caso, manteremos os estilos em um arquivo separado.

Componentes possuem metadata que definem suas propriedades. Ao criar seu componente usando o comando ng generate component <path>,  você usa essas propriedades:
Selector: Para descrever como Angular refere para o componente em templates.
Standalone: Para descrever se o componente precisa de um NgModule.
Imports: Para descrever as dependências do componente.
Template: Para descrever a marcação HTML e layout.
StyleUrls: Para listar as URLs dos arquivos CSS que o componente usa num array.


This project was generated using [Angular CLI](https://github.com/angular/angular-cli) version 19.2.11.

## Development server

To start a local development server, run:

```bash
ng serve
```

Once the server is running, open your browser and navigate to `http://localhost:4200/`. The application will automatically reload whenever you modify any of the source files.

## Code scaffolding

Angular CLI includes powerful code scaffolding tools. To generate a new component, run:

```bash
ng generate component component-name
```

For a complete list of available schematics (such as `components`, `directives`, or `pipes`), run:

```bash
ng generate --help
```

## Building

To build the project run:

```bash
ng build
```

This will compile your project and store the build artifacts in the `dist/` directory. By default, the production build optimizes your application for performance and speed.

## Running unit tests

To execute unit tests with the [Karma](https://karma-runner.github.io) test runner, use the following command:

```bash
ng test
```

## Running end-to-end tests

For end-to-end (e2e) testing, run:

```bash
ng e2e
```

Angular CLI does not come with an end-to-end testing framework by default. You can choose one that suits your needs.

## Additional Resources

For more information on using the Angular CLI, including detailed command references, visit the [Angular CLI Overview and Command Reference](https://angular.dev/tools/cli) page.



