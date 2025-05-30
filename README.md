# Portfólio de Landing Pages – Claudio Almeida Santos Júnior

Este é o meu portfólio pessoal de landing pages, criado com HTML, TailwindCSS e JavaScript. Aqui você encontrará uma coleção dos projetos que desenvolvi para clientes e estudos, organizados de forma dinâmica e acessível.

## 🚀 Tecnologias Utilizadas

- HTML5
- [Tailwind CSS](https://tailwindcss.com/)
- JavaScript (ES Modules)

## 📁 Estrutura do Projeto

```
portfolio/
├── index.html              # Página inicial com lista dos projetos
├── /assets                 # Imagens e ícones usados no site
│   └── claudio.jpg         # Sua foto de perfil
├── /js
│   └── projects.js         # Lista dinâmica dos projetos
├── /psi                    # Exemplo de landing page
│   └── index.html
├── /nutri                  # Outro exemplo de landing page
│   └── index.html
└── ...
```

## 🧠 Como funciona

Os projetos são definidos no arquivo `js/projects.js`, e cada item da lista é exibido automaticamente na homepage, com link para a pasta correspondente. Isso facilita a manutenção e a inclusão de novos trabalhos.

Exemplo de entrada no `projects.js`:

```js
const projects = [
  {
    name: "Landing Page Psicólogo",
    folder: "psi",
    image: "psi/preview.jpg"
  },
  {
    name: "Landing Page Nutricionista",
    folder: "nutri",
    image: "nutri/preview.jpg"
  }
];
```

## 👤 Sobre mim

**Claudio Almeida Santos Júnior**  
Desenvolvedor Front-end focado em experiências modernas e páginas de alta conversão.

- 🌐 Site: [claudiojr.vercel.app](https://claudiojr.vercel.app)
- 💼 LinkedIn: [linkedin.com/in/claudio-junior-537319162](https://linkedin.com/in/claudio-junior-537319162)
- 🛠 GitHub: [github.com/claudio-asj](https://github.com/claudio-asj)
- 📱 WhatsApp: +55 21 97931-7341

## 📸 Pré-visualização

![preview](assets/preview.png)

> Dica: use uma captura de tela do portfólio para mostrar visualmente a página inicial.

## 📦 Como usar

1. Clone ou baixe este repositório
2. Coloque suas páginas em pastas dentro da raiz (`/nutri`, `/psi`, etc.)
3. Atualize o `projects.js` com os nomes e caminhos
4. Abra o `index.html` no navegador!

---

Feito com 💻 por Claudio Jr.