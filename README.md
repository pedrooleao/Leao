# 🎸 Curso de Baixo — Do Básico ao Profissional

Aplicativo web completo para estudo de baixo elétrico, com 23 módulos, checklists de progresso e timer de prática.

## Deploy no Vercel

### Opção 1 — Vercel CLI (mais rápido)

```bash
# 1. Instale o Vercel CLI
npm install -g vercel

# 2. Entre na pasta do projeto
cd curso-baixo

# 3. Faça o deploy
vercel

# Siga as instruções no terminal. Em ~30 segundos o site estará no ar.
```

### Opção 2 — Vercel via GitHub (recomendado para atualizações)

1. Crie um repositório no GitHub e faça upload desta pasta
2. Acesse [vercel.com](https://vercel.com) e faça login
3. Clique em **"Add New Project"**
4. Importe o repositório do GitHub
5. Clique em **Deploy** — pronto!

### Opção 3 — Drag & Drop (mais simples, sem conta GitHub)

1. Acesse [vercel.com/new](https://vercel.com/new)
2. Arraste a pasta `curso-baixo` direto para o navegador
3. O Vercel faz o deploy automaticamente

---

## Estrutura do Projeto

```
curso-baixo/
├── index.html      # App completo (HTML + CSS + JS em um arquivo)
├── vercel.json     # Configuração do Vercel
└── README.md       # Este arquivo
```

## Tecnologias

- HTML5, CSS3, JavaScript puro (sem dependências)
- Google Fonts (carregado via CDN)
- localStorage para persistência do progresso

## Funcionalidades

- 23 módulos do básico ao profissional
- Checklists de progresso por lição
- Timer de prática integrado
- Progresso salvo no navegador do usuário
- Design responsivo (mobile + desktop)
