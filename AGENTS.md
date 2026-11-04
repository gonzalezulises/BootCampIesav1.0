# AGENTS.md — BootCampIesav1.0

Plataforma de aprendizaje en Next.js con Supabase y Drizzle.

## Comandos

- `npm run dev`: servidor local.
- `npm run typecheck && npm run lint && npm test`: verificación. Tiene que salir 0 antes de cada commit. El CI (`ci.yml`) corre además `npm run build`.
- `npm run db:generate` / `db:migrate` / `db:push` / `db:seed`: migraciones y seed con Drizzle.
- `npm run format`: Prettier sobre `src/`.

## Reglas

- Commits atómicos que expliquen el porqué.
- Si cambias el comportamiento, actualiza la documentación en el mismo commit.
