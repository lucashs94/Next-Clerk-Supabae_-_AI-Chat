# AI Chat App

Aplicacao de chat com inteligencia artificial construida com Next.js 15, React 19, Supabase e autenticacao via Clerk.

## Tech Stack

- **Framework:** Next.js 15 (App Router), React 19, TypeScript
- **Estilizacao:** Tailwind CSS
- **Auth:** Clerk
- **Database:** Supabase
- **Deploy:** Vercel-ready

## Funcionalidades

- Autenticacao de usuarios com Clerk (login, registro, sessoes)
- Interface de chat com IA
- Persistencia de conversas via Supabase
- Layout responsivo com Tailwind CSS

## Como Rodar

### Pre-requisitos
- Node.js 18+
- Conta no [Clerk](https://clerk.com) (chaves de API)
- Projeto no [Supabase](https://supabase.com) (URL + anon key)

### Setup

```bash
npm install
cp .env.example .env.local
# Preencha as variaveis do Clerk e Supabase no .env.local
npm run dev                 # inicia em http://localhost:3000
```

### Variaveis de ambiente necessarias

```
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=
NEXT_PUBLIC_SUPABASE_URL=
NEXT_PUBLIC_SUPABASE_ANON_KEY=
```

## Autor

**Lucas Silva** - [LinkedIn](https://www.linkedin.com/in/lucashs94/) | [GitHub](https://github.com/lucashs94) | h7.lucas@gmail.com
