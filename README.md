
```markdown
# Portfólio em Tailwind CSS

Este é um projeto de portfólio pessoal desenvolvido com **Tailwind CSS**.  
O objetivo é apresentar seus projetos, habilidades e informações de contato em uma página moderna, responsiva e fácil de manter.

---

## 🚀 Tecnologias

- [Tailwind CSS](https://tailwindcss.com) — Framework CSS utility-first
- HTML5
- PostCSS + Autoprefixer

---

## 📦 Instalação

Clone o repositório e instale as dependências:

```bash
git clone https://github.com/Li-code1/portfolioLilianeTailwindcss
cd portfolio-tailwind
npm install
```

---

## ⚙️ Configuração

1. Inicialize o Tailwind:
   ```bash
   npx tailwindcss init
   ```

2. Configure o arquivo `tailwind.config.js` para escanear seu `index.html`:
   ```js
   module.exports = {
     content: ["./index.html"],
     theme: {
       extend: {},
     },
     plugins: [],
   }
   ```

3. Crie o arquivo de entrada CSS (`src/input.css`):
   ```css
   @tailwind base;
   @tailwind components;
   @tailwind utilities;
   ```

---

## 🛠️ Build

Para gerar o CSS final:

```bash
npx tailwindcss -i ./src/input.css -o ./dist/styles.css --minify
```

Durante o desenvolvimento, use o modo watch:

```bash
npx tailwindcss -i ./src/input.css -o ./dist/styles.css --watch
```

---

## 📂 Estrutura

```
Projeto/
├── index.html
├── tailwind.config.js
├── postcss.config.js
├── src/
│   └── input.css
└── dist/
    └── styles.css
```


## 🎨 Personalização

- **Cores**: edite em `tailwind.config.js` dentro de `theme.extend.colors`.
- **Fontes**: adicione fontes do Google Fonts no `<head>` do `index.html`.
- **Dark mode**: habilite com `darkMode: "class"` no config.


## 📄 Licença

Este projeto está sob a licença MIT.  
Sinta-se livre para usar e modificar conforme necessário.
```

---
