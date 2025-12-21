# Next.js Dashboard

Minimal dashboard starter using the Next.js App Router.

Quick start

- Install dependencies: `pnpm install`
- Run dev server: `pnpm run dev`

Project structure and purposes

- `app/` : Next.js App Router entry. Contains global layout and top-level pages.
  - `layout.tsx` : Root layout for the app.
  - `page.tsx` : Root page / homepage for the dashboard.
- `lib/` : Shared libraries and helpers.
  - `data.ts` : Data helpers / mock data access.
  - `definitions.ts` : Type definitions and shared interfaces.
  - `placeholder-data.ts` : Example/placeholder data used in UI.
  - `utils.ts` : Utility functions.
- `query/` : API route(s) for querying data.
  - `route.ts` : Server route handling query requests.
- `seed/` : API route to seed or reset demo data.
  - `route.ts` : Seed route implementation.
- `ui/` : Reusable UI components and styling.
  - `global.css` : Global Tailwind + custom CSS.
  - `button.tsx`, `search.tsx`, `skeletons.tsx`, `login-form.tsx` : Generic UI components.
  - `acme-logo.tsx` : Example brand/logo component.
  - `customers/` : Customer-related UI (e.g., `table.tsx`).
  - `dashboard/` : Dashboard-specific components (cards, charts, nav links, sidenav).
  - `invoices/` : Invoice-related components (breadcrumbs, forms, table, pagination, status, buttons).
- `public/` : Static public assets.

- Config and meta files
  - `next.config.ts` : Next.js configuration.
  - `package.json`, `pnpm-lock.yaml` : Project dependencies and lockfile.
  - `tailwind.config.ts`, `postcss.config.js` : Tailwind / PostCSS config.
  - `tsconfig.json` : TypeScript configuration.

Purpose

This repository is a compact starter/dashboard demo demonstrating the Next.js App Router, TypeScript, Tailwind CSS, and a small component-driven UI layout. It's intended for learning, demos, and to be used as a foundation for building a simple admin/dashboard interface.

If you want me to also add running instructions, tests, or a CONTRIBUTING section, tell me which to include next.
Purpose

    This repository is a compact starter/dashboard demo demonstrating the Next.js App Router, TypeScript, Tailwind CSS, and a small component-driven UI layout. It's intended for learning, demos, and to be used as a foundation for building a simple admin/dashboard interface.

    Project hierarchy (snapshot)

    ```
    nextjs-dashboard/
    ├─ app/
    │  ├─ layout.tsx
    │  └─ page.tsx
    ├─ lib/
    │  ├─ data.ts
    │  ├─ definitions.ts
    │  ├─ placeholder-data.ts
    │  └─ utils.ts
    ├─ query/
    │  └─ route.ts
    ├─ seed/
    │  └─ route.ts
    ├─ ui/
    │  ├─ acme-logo.tsx
    │  ├─ button.tsx
    │  ├─ global.css
    │  ├─ login-form.tsx
    │  ├─ search.tsx
    │  ├─ skeletons.tsx
    │  ├─ customers/
    │  │  └─ table.tsx
    │  ├─ dashboard/
    │  │  ├─ cards.tsx
    │  │  ├─ latest-invoices.tsx
    │  │  ├─ nav-links.tsx
    │  │  ├─ revenue-chart.tsx
    │  │  └─ sidenav.tsx
    │  └─ invoices/
    │     ├─ breadcrumbs.tsx
    │     ├─ buttons.tsx
    │     ├─ create-form.tsx
    │     ├─ edit-form.tsx
    │     ├─ pagination.tsx
    │     ├─ status.tsx
    │     └─ table.tsx
    ├─ public/
    │  └─ customers/
    ├─ next.config.ts
    ├─ package.json
    ├─ pnpm-lock.yaml
    ├─ postcss.config.js
    ├─ tailwind.config.ts
    ├─ tsconfig.json
    └─ README.md

    ```

    If you'd like a different tree format (JSON, Markdown nested lists, or a graphical diagram), tell me which format you prefer and I'll update it.
