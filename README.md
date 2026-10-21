# Agent Skill Tree

An interactive experiment for designing agent capabilities through a Path-of-Exile-style allocation tree. Allocate nodes, explore archetype synergies, and export an agent specification.

**Status: public prototype.** This is a design tool, not an agent runtime or a production orchestration system.

## Stack
- Next.js 15/16 App Router + TypeScript strict
- Tailwind CSS 4
- Framer Motion
- Supabase optional persistence (`agent_builds` table in `supabase-schema.sql`)

## Env
```bash
NEXT_PUBLIC_SUPABASE_URL=
NEXT_PUBLIC_SUPABASE_ANON_KEY=
SUPABASE_SERVICE_ROLE_KEY=
```
