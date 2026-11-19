# Deployment — G6CODERS Website

## Environments

| Environment | Platform | URL |
|---|---|---|
| Production | Vercel | To confirm |
| Local | Vite | http://localhost:5173 |

## Prerequisites

- Node.js 20+
- The G6CODERS API deployed and reachable

## Secrets

| Name | Purpose | Where |
|---|---|---|
| `VITE_API_URL` | Public API base URL | Vercel environment variables |

Only `VITE_*` values are exposed to the browser. Never put a secret in a `VITE_*` variable.

## Deploy

1. Merge to `main` through a pull request.
2. Wait for CI (`npm run lint`, `npm run build`).
3. Vercel builds and deploys automatically.
4. Verify the SPA rewrites in `vercel.json`.
5. Open the site and test the home, services, projects, gallery, team, and contact sections.

## Rollback

- Promote the previous Vercel deployment.
- No database rollback is needed for the frontend.

## Owner

- Primary: `Mystral-hub`
- Backup: `Zeusse-Neumbi`

Last verified: 2026-11-19 (public URL to confirm).
