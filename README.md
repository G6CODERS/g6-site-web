# G6CODERS — Website

Public website for G6CODERS, the student-run software studio from Polytech Douala.

**Français :** [README.fr.md](README.fr.md)

## Status

Active. Public source repository.

## Features

- Home, services, projects, gallery, team, and contact sections
- Admin area for content management
- Responsive layout with light and dark themes
- Contact form backed by the G6CODERS API

## Stack

| Layer | Technology |
|---|---|
| UI | React 19, TypeScript |
| Build | Vite |
| Routing | React Router |
| Styling | Tailwind CSS 4, shadcn-style components |
| Forms | React Hook Form, Zod |
| HTTP | Axios |

## Getting started

Prerequisites: Node.js 20+.

```bash
npm ci
cp .env.example .env
# VITE_API_URL=http://localhost:8000
npm run dev
```

Useful commands:

```bash
npm run build
npm run lint
npm run preview
```

## Deployment

Deployed on Vercel. SPA rewrites are configured in [`vercel.json`](vercel.json).

See [DEPLOYMENT.md](DEPLOYMENT.md) for the runbook and rollback.

## Security

- No secrets in the frontend. Only `VITE_*` values that are safe to expose.
- Report vulnerabilities privately via the organization [security policy](https://github.com/G6CODERS/.github/blob/main/SECURITY.md).

## Maintainers

- `Mystral-hub` — lead
- `Zeusse-Neumbi` — owner

## License

License to be decided by the owners. Until then, all rights are reserved.
