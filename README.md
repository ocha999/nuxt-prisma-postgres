# Nuxt Minimal Starter

## 目的

Nuxt 4 と Prisma を使用した最小限のスターター テンプレートを提供することを目的としています。このテンプレートは、PostgreSQL データベースとの接続を実装しており、Nuxt 4 アプリケーションで Prisma を使用するための出発点として機能します。

## インストール済みパッケージ

### Dependencies
- `@prisma/adapter-pg` (^8.0.0) - PostgreSQL adapter for Prisma
- `@prisma/client` (^8.0.0) - Prisma Client for database access
- `dotenv` (^17.2.4) - Environment variable management
- `nuxt` (^4.2.2) - Nuxt framework
- `pg` (^8.16.4) - PostgreSQL client
- `tsx` (^4.20.7) - TypeScript execute
- `vue` (^3.5.26) - Vue.js framework
- `vue-router` (^4.6.4) - Vue Router

### DevDependencies
- `@types/pg` (^8.15.7) - TypeScript types for pg
- `prisma` (^7.2.0) - Prisma CLI

## 概要

Look at the [Nuxt documentation](https://nuxt.com/docs/getting-started/introduction) to learn more.

## Setup

Make sure to install dependencies:

```bash
# npm
npm install

# pnpm
pnpm install

# yarn
yarn install

# bun
bun install
```

## Development Server

Start the development server on `http://localhost:3000`:

```bash
# npm
npm run dev

# pnpm
pnpm dev

# yarn
yarn dev

# bun
bun run dev
```

## Production

Build the application for production:

```bash
# npm
npm run build

# pnpm
pnpm build

# yarn
yarn build

# bun
bun run build
```

Locally preview production build:

```bash
# npm
npm run preview

# pnpm
pnpm preview

# yarn
yarn preview

# bun
bun run preview
```

Check out the [deployment documentation](https://nuxt.com/docs/getting-started/deployment) for more information.
