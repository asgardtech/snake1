# Codebase Overview

This repository is a minimal Vite + React + TypeScript starter powered by the LACC stack. The code is organized into the following top‑level directories and files:

## Root
- `package.json` – dependencies, scripts, and Bun config.
- `vite.config.ts` – Vite build config.
- `tailwind.config.ts` – Tailwind CSS configuration.
- `postcss.config.js` – PostCSS config used by Tailwind.
- `tsconfig.json` – TypeScript compiler options.
- `tsconfig.app.json` & `tsconfig.node.json` – extended configs for the app and Node.
- `.env.example` – example environment variables.
- `README.md` – project description and usage.
- `LICENSE` – MIT license.
- `.editorconfig` – editor defaults.
- `components.json` – shadcn component config.
- `.github` – GitHub workflow templates.

## `src` Directory
- `index.css` – global Tailwind imports and base styles.
- `main.tsx` – React entry point, sets up routing, query client, and toasters.
- `App.tsx` – root component with routing.
- `App.test.tsx` – unit test for the root component.
- `test/setup.ts` – test setup file.
- `components/ui/button.tsx` – reusable shadcn‑styled button component.
- `lib/utils.ts` – small utility for class name merging (`cn`).
- `lib/supabase.ts` – initializes the Supabase client using environment variables.

## Future Expansion
The current structure is intentionally flat. As the project grows, additional sub‑directories like `components`, `pages`, `hooks`, and `services` can be added.

---

This document is generated to help onboard new contributors and to serve as a quick reference for the existing code structure.