# Designops Copilot

Designops Copilot is a Next.js app for a Figma-to-React editing workflow. The project is set up as a typed React frontend with Tailwind styling, reusable UI primitives, and runtime environment validation.

## What this project includes

- App Router setup with Next.js 15 and React 19
- TypeScript-first frontend codebase
- Tailwind CSS styling with shadcn/ui-compatible components
- Radix UI primitives for accessible building blocks
- Zod-based environment validation at startup
- Small utility layer for shared helpers and logging

## Stack

- [Next.js 15](https://nextjs.org/)
- [React 19](https://react.dev/)
- [TypeScript](https://www.typescriptlang.org/)
- [Tailwind CSS](https://tailwindcss.com/)
- [Radix UI](https://www.radix-ui.com/)
- [shadcn/ui](https://ui.shadcn.com/)
- [Zod](https://zod.dev/)

## Getting started

1. Install dependencies:

```bash
npm install
```

2. Create a `.env.local` file:

```bash
NEXT_PUBLIC_APP_URL=http://localhost:3000
```

3. Start the development server:

```bash
npm run dev
```

4. Open `http://localhost:3000`.

## Available scripts

- `npm run dev` starts the app in development mode with Turbopack
- `npm run build` creates a production build
- `npm run start` serves the production build
- `npm run lint` runs the Next.js linter
- `npm run format` formats supported source files with Prettier

## Project structure

- `src/app/page.tsx` contains the current landing page
- `src/app/layout.tsx` defines the root layout
- `src/app/globals.css` contains global styles
- `src/components/ui/` contains shared UI primitives
- `src/config/env.ts` validates required environment variables
- `src/lib/utils.ts` contains shared utility helpers
- `src/utils/logger.ts` contains the application logger

## Environment

The app validates environment variables on startup. At the moment, these values are required:

- `NODE_ENV`
- `NEXT_PUBLIC_APP_URL`

If either value is missing or invalid, the app throws during initialization with a clear error message.
