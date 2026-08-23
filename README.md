# EasyTransfer

EasyTransfer is a React + Vite website for private airport transfers in Türkiye.

## Requirements

- Node.js 20 or newer
- pnpm 10 or newer

## Install and run locally

```bash
pnpm install --frozen-lockfile
pnpm --filter @workspace/mockup-sandbox run dev
```

Open the local URL shown by Vite (normally `http://localhost:5173`).

## Production build

```bash
pnpm run build
```

The static website build is written to `artifacts/mockup-sandbox/dist`.

## Replit preview

Replit supplies the `PORT` and `BASE_PATH` variables automatically. For local work they are optional: the site uses port `5173` and base path `/` by default.

## Project structure

- `artifacts/mockup-sandbox` — EasyTransfer website and local images
- `artifacts/api-server` — API server scaffold
- `lib` — shared API and database libraries