# TikTok Shop Afiliado

Este é um app simples em **React + Vite** para divulgar links de produtos como afiliado do **TikTok Shop**.

🚀 Deploy automático configurado com **GitHub Actions** no **GitHub Pages**.

---

## 🔧 Como rodar localmente

```bash
# Instalar dependências
npm install

# Rodar em desenvolvimento
npm run dev

# Build de produção
npm run build
```

---

## 🚀 Deploy Automático

Já está configurado um workflow em `.github/workflows/deploy.yml`.

Sempre que fizer **push na branch `main`**, o GitHub Actions vai:

1. Instalar dependências
2. Rodar `npm run build`
3. Publicar no branch `gh-pages`
4. Atualizar automaticamente o site em:

👉 https://pixjorgebravo-web.github.io/tiktok

---

## 📂 Estrutura

```
tiktok-shop-afiliado/
├── src/
│   ├── App.jsx
│   └── main.jsx
├── index.html
├── vite.config.js
├── package.json
└── .github/
    └── workflows/
        └── deploy.yml
```

---

## ✨ Personalização

- Edite os links de produtos dentro de `src/App.jsx`.
- Troque o `base: '/tiktok/'` no `vite.config.js` caso altere o nome do repositório no GitHub.

---
Feito com ❤️ e React.
