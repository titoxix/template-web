# Template Web

Mobile-first web template with configuration and libraries pre-installed.

## Stack

- **Framework:** Next.js 16 (App Router)
- **ORM:** Prisma 7
- **Validation:** Zod 4
- **UI:** shadcn/ui (Radix, Nova preset) + Tailwind CSS 4
- **Testing:** Vitest + React Testing Library
- **Linting/Formatting:** Biome 2
- **Language:** TypeScript
- **Node:** 22.20.0

## Requirements

- Node 22.20.0 (use `nvm use`)
- pnpm

## Development

```bash
pnpm install
pnpm dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser.

## Scripts

| Command | Description |
|---|---|
| `pnpm dev` | Development server |
| `pnpm build` | Production build |
| `pnpm test` | Tests in watch mode |
| `pnpm test:run` | Tests in CI mode |
| `pnpm check` | Lint + format (read-only) |
| `pnpm check:fix` | Lint + format with auto-fix |

## Architecture

See [AGENTS.md](./AGENTS.md) for full architecture and conventions documentation.
