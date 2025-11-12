🔎 Github Finder

O Github Finder é uma aplicação web que permite buscar usuários do GitHub e visualizar informações detalhadas sobre seus perfis e principais repositórios.

O usuário pode digitar o nome de um perfil no campo de pesquisa, e ao clicar no botão (ou pressionar Enter), será redirecionado para a página do usuário com informações como:

👤 Nome

📍 Localidade

👥 Seguidores

➡️ Seguindo

Além disso, é possível navegar para a seção de melhores repositórios, onde serão exibidos os 5 projetos mais bem ranqueados do usuário, com a opção de acessar o GitHub diretamente para visualizar o código.

✨ Funcionalidades

🔎 Buscar usuários do GitHub por nome

📄 Página com informações do perfil (nome, localidade, seguidores e seguindo)

📂 Listagem dos 5 principais repositórios do usuário

🔗 Link direto para o GitHub de cada repositório

🔄 Navegação entre páginas utilizando React Router DOM

🎨 Interface estilizada com CSS Modules

🖼️ Ícones interativos com React Icons

🛠️ Tecnologias Utilizadas:

React

TypeScript

CSS Modules

React Router DOM

React Icons

GitHub REST API


🚀 Como Executar o Projeto

Clone o repositório:

git clone https://github.com/seu-usuario/github_finder.git


Entre na pasta do projeto:

cd github_finder


Instale as dependências:

npm install


Configure sua chave de acesso (se necessário) no .env:

VITE_GITHUB_TOKEN=sua_chave_aqui


Rode o projeto:

npm run dev


Abra no navegador:

http://localhost:5173

📂 Estrutura do Projeto
github_finder/
├── public/
├── src/
│   ├── components/
│   ├── pages/
│   ├── services/
│   ├── styles/
│   ├── App.tsx
│   ├── main.tsx
│   └── types/
├── package.json
├── tsconfig.json
└── README.md

🔗 Deploy

👉 https://github-finder-virid-tau.vercel.app/

🤝 Contribuições

Contribuições são muito bem-vindas!
Sinta-se à vontade para abrir uma issue ou enviar um pull request.
