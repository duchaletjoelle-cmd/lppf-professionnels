# lppf-professionnels

Site Les Petits Papiers Faciles — géré via le QG IA.

## Branches
- `main` → Production (Sandra valide avant merge)
- `staging` → Pré-production (agents travaillent ici)
- `agent/*` → Branches de travail des agents

## Structure
- `/content` — Articles, pages, textes SEO (Léa)
- `/assets/images` — Visuels, photos (Maya)
- `/seo` — Méta-balises, sitemap, robots.txt (Paul)
- `/scripts` — JavaScript custom (Paul)

## Workflow
1. Agent génère le contenu dans le QG
2. QG pousse sur une branche `agent/nom-mission`
3. Pull Request vers `staging`
4. Sandra approuve → merge → `main`
5. GitHub Actions déploie vers IONOS (FTP)

_Géré automatiquement par le QG Les Petits Papiers Faciles_
