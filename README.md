# Sigly

Plataforma de assinatura eletronica de documentos conforme Lei 14.063/2020 (Assinatura Simples).

## Stack

- **Framework:** Next.js 16 (App Router) + TypeScript
- **Estilizacao:** Tailwind CSS v4 + shadcn/ui (Vega + Radix)
- **Banco:** PostgreSQL (Neon) + Prisma 7
- **Auth:** NextAuth v4 (Google OAuth + Email magic link)
- **Storage:** Vercel Blob (PDFs originais e finais)
- **Email:** Resend
- **PDF:** pdf-lib + qrcode (manifesto de assinatura)
- **Pagamento:** Stripe
- **Hosting:** Vercel

## Desenvolvimento local

```bash
npm install
npm run dev
```

Acesse http://localhost:3000

## Variaveis de ambiente

Copie `.env.example` para `.env.local` e preencha com valores reais.
Nunca commite `.env.local`.

## Status do projeto

Em desenvolvimento - Fase 1 (setup) concluida.

## Licenca

Privado - todos os direitos reservados.
