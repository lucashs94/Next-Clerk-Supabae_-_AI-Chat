# AI Chat App

An AI-powered chat application built with Next.js 15, React 19, Supabase, and Clerk authentication.

## Tech Stack

- **Framework:** Next.js 15 (App Router), React 19, TypeScript
- **Styling:** Tailwind CSS
- **Auth:** Clerk
- **Database:** Supabase
- **Deploy:** Vercel-ready

## Features

- User authentication with Clerk (login, registration, sessions)
- AI-powered chat interface
- Conversation persistence via Supabase
- Responsive layout with Tailwind CSS

## Getting Started

### Prerequisites
- Node.js 18+
- [Clerk](https://clerk.com) account (API keys)
- [Supabase](https://supabase.com) project (URL + anon key)

### Setup

```bash
npm install
cp .env.example .env.local
# Fill in the Clerk and Supabase variables
npm run dev                 # starts at http://localhost:3000
```

### Environment Variables

```
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=
NEXT_PUBLIC_SUPABASE_URL=
NEXT_PUBLIC_SUPABASE_ANON_KEY=
```