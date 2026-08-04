SPRINT 05 — FIRST COLLECTION (ACERVO DO GOL)

Sprint 05 has two equally important objectives:

1. Complete the migration to the production Supabase project.
2. Publish the first real collection of Acervo do Gol.

This sprint marks the transition from prototype to living archive.

=========================================================
GENERAL RULES
=========================================================

Do NOT redesign the interface.

Do NOT change the visual identity.

Do NOT modify navigation.

Do NOT change the project architecture.

Keep the current user experience.

The goal is making the existing site become a real football archive.

=========================================================
MODULE 01
PRODUCTION DATABASE
=========================================================

Connect the project to the production Supabase project.

The production database becomes the ONLY source of truth.

Tasks:

• Connect to the new Supabase project.

• Apply every existing migration.

• Recreate schema if necessary.

• Recreate RLS policies.

• Validate relationships.

• Remove dependency on fixtures.ts.

• Every page must consume data through atlas.functions.ts.

Validate:

Players

Clubs

Competitions

Goals

Rankings

Everything must be loaded from Supabase.

=========================================================
MODULE 02
FIRST COLLECTION
=========================================================

Integrate the editorial collection supplied by the project.

Collections:

Players

• Pelé

• Lionel Messi

• Cristiano Ronaldo

• Romário

• Zico

Clubs

• Santos

• Barcelona

• Flamengo

• Real Madrid

• Manchester United

Competitions

• FIFA World Cup

• UEFA Champions League

• Copa Libertadores

• Campeonato Brasileiro

• Copa América

Historical Goals

The project team will provide the first historical goals.

Do NOT invent football facts.

Do NOT generate biographies.

Do NOT create fictional content.

Only integrate editorial content supplied by the project.

=========================================================
MODULE 03
RELATIONSHIPS
=========================================================

Every entity must already feel interconnected.

Examples:

Player

↓

Goals

↓

Competition

↓

Club

↓

Related Players

↓

Rankings

Users should naturally continue browsing.

Avoid dead-end pages.

=========================================================
MODULE 04
QUALITY
=========================================================

Validate:

Responsive layout.

Navigation.

Internal links.

Database queries.

SEO metadata.

No broken routes.

No console errors.

=========================================================
DELIVERABLES
=========================================================

At the end provide:

1. Migration summary.

2. Database status.

3. Tables updated.

4. Editorial content integrated.

5. Files modified.

6. Components modified.

7. Recommendations before Sprint 06.

Stop after Sprint 05.
