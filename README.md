# Quant Reality Check

An evidence-led career-exploration prototype for the Catalyst 2026 Fundamentum track. It contains 23 reviewed early-career roles across eight selected quantitative trading, market-making and investment firms.

## Quick preview and GitHub Pages

The repository-root `index.html` is a self-contained version of the website. It can be opened directly without installing dependencies, and it is the file published by GitHub Pages.

## Local setup

Requirements: Node.js 22.13 or newer.

```bash
npm install
npm run dev
```

Then open `http://localhost:3000`.

For a production build:

```bash
npm run build
npm run start
```

`pnpm install`, `pnpm run dev`, `pnpm run build` and `pnpm run start` are also supported.

## Main files

- `app/page.tsx` — single-page interface and interactions
- `app/globals.css` — responsive visual system
- `app/data.ts` — the 23 workbook-derived role records
- `app/exploration.ts` — visible deterministic exploration rules
- `app/layout.tsx` — page and social-preview metadata
- `public/og.png` — social sharing card
- `tests/rendered-html.test.mjs` — source and guardrail checks

The application uses browser `localStorage` only for in-progress answers. It has no login, backend, paid API or external runtime dependency.

## Domain options

The current public Sites address can remain as a test URL. To use a custom domain, add the hostname in Sites and copy the returned DNS records into the domain provider. DNS and SSL activation can take time after the records are added.

Changing the Sites URL label and binding a separately owned custom domain are different operations. Do not change `metadataBase` in `app/layout.tsx` until the new public origin is active.

## Evidence guardrails

Company, role, eligibility, status and source facts come only from the validated workbook supplied for this project. The Research Journey reports the supplied convenience-sample survey and interview findings with their limitations. Missing fields are shown as “Not stated in reviewed source.”
