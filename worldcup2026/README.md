# ⚽ FIFA World Cup 2026™ — Site Promocional

Site promocional da Copa do Mundo 2026 (EUA, Canadá e México), desenvolvido em **Node.js + Express**, pronto para deploy no **Vercel**.

## 🚀 Como rodar localmente

```bash
# 1. Instalar dependências
npm install

# 2. Iniciar servidor
npm start

# 3. Abrir no navegador
http://localhost:3000
```

## ☁️ Como subir no Vercel

### Opção 1 — Via Vercel CLI (recomendado)

```bash
# 1. Instalar Vercel CLI globalmente
npm install -g vercel

# 2. Fazer login
vercel login

# 3. Deploy (na pasta do projeto)
vercel

# 4. Para deploy em produção
vercel --prod
```

### Opção 2 — Via GitHub + Vercel Dashboard

1. Crie um repositório no GitHub e faça push do projeto:
   ```bash
   git init
   git add .
   git commit -m "feat: site copa do mundo 2026"
   git remote add origin https://github.com/SEU_USER/SEU_REPO.git
   git push -u origin main
   ```
2. Acesse [vercel.com](https://vercel.com) e faça login
3. Clique em **"Add New Project"**
4. Importe o repositório do GitHub
5. Vercel detecta o `vercel.json` automaticamente — clique **Deploy**
6. ✅ Seu site estará no ar com uma URL `.vercel.app`

## 📁 Estrutura do Projeto

```
worldcup2026/
├── index.js          # Servidor Node.js + Express
├── package.json      # Dependências
├── vercel.json       # Configuração do Vercel
├── .gitignore
└── public/
    └── index.html    # Página principal do site
```

## ✏️ Personalizar

- **Conteúdo**: edite `public/index.html`
- **Link de cadastro**: no HTML, busque por `"Acessar Portal de Cadastro da FIFA"` e troque o `href` pelo link desejado
- **Porta local**: defina a variável de ambiente `PORT` ou edite `index.js`
