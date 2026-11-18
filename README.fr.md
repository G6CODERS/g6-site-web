# G6CODERS — Site web

Site public de G6CODERS, le studio logiciel étudiant de Polytech Douala.

**English:** [README.md](README.md)

## Statut

Actif. Dépôt public.

## Fonctionnalités

- Sections accueil, services, projets, galerie, équipe et contact
- Espace administrateur pour la gestion du contenu
- Mise en page responsive avec thèmes clair et sombre
- Formulaire de contact connecté à l'API G6CODERS

## Stack

| Couche | Technologie |
|---|---|
| UI | React 19, TypeScript |
| Build | Vite |
| Routage | React Router |
| Styles | Tailwind CSS 4, composants de type shadcn |
| Formulaires | React Hook Form, Zod |
| HTTP | Axios |

## Démarrage

Prérequis : Node.js 20+.

```bash
npm ci
cp .env.example .env
# VITE_API_URL=http://localhost:8000
npm run dev
```

Commandes utiles :

```bash
npm run build
npm run lint
npm run preview
```

## Déploiement

Déployé sur Vercel. Les rewrites SPA sont configurés dans [`vercel.json`](vercel.json).

## Sécurité

- Aucun secret dans le frontend. Uniquement des valeurs `VITE_*` sûres à exposer.
- Signaler les vulnérabilités via la [politique de sécurité](https://github.com/G6CODERS/.github/blob/main/SECURITY.md) de l'organisation.

## Mainteneurs

- `Mystral-hub` — responsable
- `Zeusse-Neumbi` — owner

## Licence

Licence à décider par les owners. En attendant, tous droits réservés.
