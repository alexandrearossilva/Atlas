Sprint 04 is officially approved.

Do NOT redesign the interface.

Do NOT modify the visual identity created in Sprint 02.

Do NOT change the navigation.

Do NOT change the existing architecture.

This sprint is NOT about creating new pages.

It is about preparing Acervo do Gol to become a real data-driven platform.

==========================================================
MAIN OBJECTIVE
==========================================================

Transform the project from a static prototype into a platform ready to receive real editorial content.

This sprint is divided into two modules.

==========================================================
MODULE 01
DATA FOUNDATION
==========================================================

Configure Supabase.

Connect the project.

Create the complete initial data structure.

Prepare the application for future CRUD operations.

Create the following entities:

• Player

• Club

• Competition

• Goal

• Ranking

Prepare relationships between entities.

Examples:

Player → many Goals

Club → many Players

Club → many Goals

Competition → many Goals

Ranking → many Goals

Ranking → many Players

Create clean typed services.

Follow the current project architecture.

Do NOT implement authentication.

Do NOT implement Admin.

Do NOT implement CRUD screens.

Do NOT implement content editing.

Only prepare the data layer.

==========================================================
MODULE 02
MVP SEED
==========================================================

The project team will provide editorial content.

Do NOT generate biographies.

Do NOT generate football facts.

Do NOT invent statistics.

Use ONLY the editorial content supplied by the project.

The goal is validating the platform using real content.

Initially populate:

PLAYERS

• Pelé

• Lionel Messi

• Cristiano Ronaldo

• Romário

• Zico

CLUBS

• Santos

• Barcelona

• Flamengo

• Real Madrid

• Manchester United

COMPETITIONS

• FIFA World Cup

• UEFA Champions League

• Copa Libertadores

• Campeonato Brasileiro

• Copa América

Render the supplied information correctly inside the existing pages.

Relationships must already work.

Example:

Pelé page links to Santos.

Santos page links back to Pelé.

World Cup page links to Pelé.

Navigation should already feel interconnected.

==========================================================
OUT OF SCOPE
==========================================================

No Goal registration yet.

No CMS.

No Admin.

No Login.

No User Accounts.

No Favorites.

No Comments.

No Search Engine.

No Filters.

No Analytics.

No Monetization.

==========================================================
WHEN FINISHED
==========================================================

Provide:

1. Summary of implementation.

2. Supabase configuration.

3. Database schema.

4. Files created.

5. Files modified.

6. Components created.

7. How the editorial seed was integrated.

Stop after Sprint 04.