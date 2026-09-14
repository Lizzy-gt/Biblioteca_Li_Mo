# 📚Biblioteca Limo

### Instalação do Tailwindcss no VSCODE:
Primeiro criamos o projeto que teria como base o tailwind
````
1. npm init -y 
2. npm install -D tailwindcss@3
3. npx tailwindcss init - ele vai gerar o arquivo tailwind.config.js
````
O arquivo __tailwind.config.js__ de conter:

__/** @type {import('tailwindcss').Config} */
module.exports = {
  content: ["./index.html"],
  theme: {
    extend: {},
  },
  plugins: [],
};__

### Dentro de input.css: 
```
@tailwind base;
@tailwind components;
@tailwind utilities;
```
### Comandos que utilizamos no terminal para a instalação:
````
npx tailwindcss -i ./input.css -o ./output.css --watch

npx tailwindcss -i ./input.css -o ./output.css --minify = Para gerar a versão final do projeto
````

### 👽 Paletas de cores:
````
#16A34A → bg-green-600 (Fica no navbar e no contorno do card)
#ffffff → bg-white (O fundo do site e dos cards)
#14532D → border-green-700 (Título do resumo ou dos cards)
#BBF7D0 → hover:text-green-200 (As palavras das seções)
#22C55E → border-green-500 (Cores dos textos de resumo e da apresentação)
#fbbf24 → border-amber-400 (Cor do card de destaque.)
````

### Depois organizamos as pastas na ordem sugerida pelo professor

````
Biblioteca_Li_Mo/
├── src/  
│   ├── img/                 
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
````
Depois pensamos em ideias do que seria o projeto, e decidimos fazer uma pagína que conteria varias obras, e também teria uma breve descricao dela com pequenos resumos para que as pessoas se interessasem e passasem a ler mais livros.


Criamos o site com base na estrutura que aprendemos e testamos em uma formativa, escolhemos o tailwind por possuir o css praticamente pronto no HTML porem sua instalação é mais complicada e foi a onde mais pendemos.

# Integrantes: Luiz e Monique
