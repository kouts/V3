# V3 Template

A Vue, TRPC & Prisma starter template, inspired by the T3 Stack. This template includes:

- Nuxt 3
- Tailwind
- Typescript
- TS-Pattern
- Prisma
- Zod
- TRPC


### Prerequisites

Before using this template, ensure you have node, npm and pnpm installed. pnpm is used for installing and updating packages.

### Installation & Getting Started

Installs dependencies & generate Prisma types

```pnpm i && pnpm run prisma:generate```

Generate your first migration:

```pnpm run prisma:migrate```

Seeds the Db

```pnpm run prisma:seed```

Now run the below command to start the sevrer:

```pnpm run dev```


Read the docs/GUIDE.md for more information.