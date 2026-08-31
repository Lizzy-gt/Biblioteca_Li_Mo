# Biblioteca_Li_Mo

Primeiro criamos o projeto que teria como base o tailwind
npm init -y 
npm install -D tailwindcss@3
npx tailwindcss init - ele vai gerar o arquivo tailwind.config.js
nele deve colocar dentro:

/** @type {import('tailwindcss').Config} */
module.exports = {
  content: ["./index.html"],
  theme: {
    extend: {},
  },
  plugins: [],
};

Dentro de input.css: 
@tailwind base;
@tailwind components;
@tailwind utilities;

npx tailwindcss -i ./input.css -o ./output.css --watch

npx tailwindcss -i ./input.css -o ./output.css --minify = Para gerar a versão final do projeto




Depois organizamos as pastas na ordem sugerida pelo professor

Biblioteca_Li_Mo/
├── src/  
│   ├── img/                 
│   │   
│   └── js/
│       └── script.js
├─            
|__output.css  
├── input.css         
├── index.html
├── .gitignore
├── LICENSE
├── package.json
├── package-lock.json
├── README.md
└── tailwind.config.js

Depois pensamos na ideia oque seria o projeto e decidimos fazer uma pagína que conteria varias obras que teria uma breve descricao dela tipo resumos para que as pessoas se interessasem e passasem a ler mais livros.


Criamos o site com base na estrutura que aprendemos e testamos em uma formativa escolhemos o tailwind por possuir o css praticamente pronto porem sua instalação é mais complicada.

