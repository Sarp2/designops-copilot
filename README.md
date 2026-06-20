# Design Copilot Demo 3 1aaaa1

A Figma-to-React editor that bridges design and code — apply design system changes from Figma directly to your React codebase, safely and in real time.

## Tech Stack

- [Next.js 15](https://nextjs.org) — React framework with Turbopack
- [React 19](https://react.dev) — UI library
- [TypeScript 5](https://www.typescriptlang.org/) — Type safety with strict mode
- [Tailwind CSS](https://tailwindcss.com) — Utility-first styling
- [Shadcn UI](https://ui.shadcn.com/) — Component library built on Radix UI
- [Zod](https://zod.dev) — Schema validation for forms and environment config
- [React Hook Form](https://react-hook-form.com) — Performant form management

## Getting Started

### 1. Install dependencies

```bash
npm install
```

### 2. Configure environment variables

Copy the example env file and fill in the required values:

```bash
cp .env.example .env.local
```

Required variables:

| Variable | Description |
|---|---|
| `NEXT_PUBLIC_APP_URL` | The public URL of the app (e.g. `http://localhost:3000`) |

aaaaaıaaaı

### 3. Start the development server

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) to see the application.

## Scripts

| Command | Description |
|---|---|
| `npm run dev` | Start dev server with Turbopack hot reload |
| `npm run build` | Build for production |
| `npm start` | Run the production build |
| `npm run lint` | Run ESLint |
| `npm run format` | Format code with Prettier |

## Project Structure

```
src/
├── app/
│   ├── layout.tsx        # Root layout (fonts, metadata)
│   ├── page.tsx          # Landing page
│   └── globals.css       # Global styles
├── components/
│   └── ui/               # Shadcn UI components (Button, Card, ...)
├── config/
│   └── env.ts            # Environment variable validation (Zod)
├── lib/
│   └── utils.ts          # cn() utility for Tailwind class merging
└── utils/
    └── logger.ts         # Server-side logger with levels and contexta
```
a
aaa
sbsbbsbs
sdınwısdn2oıud23dsıou2n23ıounsıun
shsusuwhsuwhsusıhwıwushıuswhısuwhwshuıwsuhı