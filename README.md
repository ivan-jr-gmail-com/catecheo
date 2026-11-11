# Catecheo

Multi-tenant web app for administering OCIA programs in Catholic parishes. Bilingual (English / Spanish).

## Development

Requires Node 24.

```bash
npm install
npm run dev        # http://localhost:3000
npm run lint
npm run typecheck
npm run build
```

Environment variables are documented in `.env.example` (added as services are connected). Real `.env*` files are never committed.
