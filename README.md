# Agent Skill Tree

## What this is

Agent Skill Tree is a product experiment for designing agent capabilities through a Path-of-Exile-style allocation tree. It helps turn vague agent roles into explicit skills, tradeoffs, and exportable specs.

Status: experiment. Useful as a design/prototyping surface, not a core operating system.

Path of Exile style passive tree for agent capabilities. Allocate nodes, reveal archetype synergies, and export a working agent spec.

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
