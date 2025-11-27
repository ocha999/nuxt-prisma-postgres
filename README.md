# Nuxt Minimal Starter

## 目的

Nuxt 4 と Prisma を使用した最小限のスターター テンプレートを提供することを目的としています。このテンプレートは、PostgreSQL データベースとの接続を実装しており、Nuxt 4 アプリケーションで Prisma を使用するための出発点として機能します。

## インストール済みパッケージ

### Dependencies
- `@prisma/adapter-pg` (^7.0.1) - PostgreSQL adapter for Prisma
- `@prisma/client` (^7.0.1) - Prisma Client for database access
- `dotenv` (^17.2.3) - Environment variable management
- `nuxt` (^4.2.1) - Nuxt framework
- `pg` (^8.16.3) - PostgreSQL client
- `tsx` (^4.20.6) - TypeScript execute
- `vue` (^3.5.25) - Vue.js framework
- `vue-router` (^4.6.3) - Vue Router

### DevDependencies
- `@types/pg` (^8.15.6) - TypeScript types for pg
- `prisma` (^7.0.1) - Prisma CLI

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
