Projeto "Sobre Mim"
Este projeto é uma página pessoal desenvolvida com Angular, criada como parte da disciplina de Arquitetura de Front-end na pós-graduação em Engenharia de Software.

Estrutura do Projeto
A estrutura do projeto é organizada da seguinte forma:

plaintext
Copiar código
src/
│
├── app/
│   ├── header/
│   │   ├── header.component.ts
│   │   ├── header.component.html
│   │   └── header.component.css
│   │
│   ├── about/
│   │   ├── about.component.ts
│   │   ├── about.component.html
│   │   └── about.component.css
│   │
│   ├── contact/
│   │   ├── contact.component.ts
│   │   ├── contact.component.html
│   │   └── contact.component.css
│   │
│   ├── app.component.ts
│   ├── app.component.html
│   └── app.component.css
Componentes
HeaderComponent: Exibe o cabeçalho da página, com o nome e um menu de navegação.
AboutComponent: Fornece informações sobre você, como experiência e interesses.
ContactComponent: Oferece detalhes de contato, incluindo links para redes sociais e email.
Configuração do Projeto
1. Clone o Repositório
Clone o repositório para sua máquina local:

bash
Copiar código
git clone https://github.com/fernanda-nascimento/frontend-bio.git
2. Instale as Dependências
Navegue até o diretório do projeto e instale as dependências:

bash
Copiar código
cd frontend-bio
npm install
3. Inicie o Servidor de Desenvolvimento
Execute o seguinte comando para iniciar o servidor e visualizar o projeto:

bash
Copiar código
ng serve
Abra seu navegador e acesse http://localhost:4200 para ver o projeto em execução.