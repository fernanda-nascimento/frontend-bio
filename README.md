# Projeto "Sobre Mim"

  

Este projeto é um exemplo simples de uma página pessoal desenvolvida com Angular. Ele serve como um projeto para a disciplina de Arquitetura de Front-end na pós-graduação em Engenharia de Software.

  

## Estrutura do Projeto

  

A estrutura do projeto é a seguinte:

  

```plaintext

src/
│

├── app/

│ ├── header/

│ │ ├── header.component.ts

│ │ ├── header.component.html

│ │ └── header.component.css

│ │

│ ├── about/

│ │ ├── about.component.ts

│ │ ├── about.component.html

│ │ └── about.component.css

│ │

│ ├── contact/

│ │ ├── contact.component.ts

│ │ ├── contact.component.html

│ │ └── contact.component.css

│ │

│ └── app.component.ts

│ app.component.html

│ app.component.css

```

## Componentes

  

- **HeaderComponent**: Exibe o cabeçalho da página, incluindo seu nome e um menu de navegação simples.

- **AboutComponent**: Contém informações sobre você, como sua experiência e interesses.

- **ContactComponent**: Fornece informações de contato, como links para suas redes sociais e email.

  

## Configuração do Projeto

  

1. **Clone o Repositório**

  

```bash

git clone https://github.com/fernanda-nascimento/frontend-bio.git
  
```
## Instale as Dependências

  

2. **Instale as Dependências**

Navegue até o diretório do projeto e instale as dependências:

  
  

```bash

cd frontend-bio

npm install

  ```

## Inicie o Servidor de Desenvolvimento

  

Execute o comando abaixo para iniciar o servidor e ver o projeto em seu navegador:

  

```bash

ng serve

Abra seu navegador e acesse http://localhost:4200 para visualizar o projeto.