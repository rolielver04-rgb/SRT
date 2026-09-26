# SRT — Sistema de Reclutamiento y Talento

ATS (Applicant Tracking System) multi-tenant, escalable vertical y horizontalmente.

## Estructura
- `apps/api` — Backend (Fastify + Prisma)
- `apps/web` — Frontend (Next.js) [próximamente]
- `packages/shared` — Tipos y utilidades compartidas

## Desarrollo
\`\`\`bash
npm install
npm --workspace apps/api run prisma generate
npm --workspace apps/api run db:push
npm --workspace apps/api run dev
\`\`\`