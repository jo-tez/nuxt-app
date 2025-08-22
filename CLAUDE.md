# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a Nuxt 4 application using TypeScript and Vue 3. The project uses pnpm as the package manager and includes ESLint for code quality, Nuxt UI for components, Nuxt Image for optimized images, and Pinia for state management.

## Development Commands

**Package Manager**: Uses `pnpm` (preferred over npm/yarn)

**Install dependencies**:
```bash
pnpm install
```

**Development server** (runs on http://localhost:3000):
```bash
pnpm dev
```

**Build for production**:
```bash
pnpm build
```

**Preview production build locally**:
```bash
pnpm preview
```

**Generate static site**:
```bash
pnpm generate
```

**Linting**:
ESLint is configured via `@nuxt/eslint` module. Check scripts in package.json or use IDE integration.

## Architecture

- **Framework**: Nuxt 4 with Vue 3 and TypeScript
- **Styling**: Nuxt UI components
- **State Management**: Pinia (configured via `@pinia/nuxt`)
- **Images**: Nuxt Image module for optimization
- **Configuration**: `nuxt.config.ts` with modules for ESLint, Image, UI, and Pinia
- **Entry Point**: `app/app.vue` contains the main app template
- **ESLint**: Uses Nuxt's ESLint configuration via `.nuxt/eslint.config.mjs`

## Key Configuration Files

- `nuxt.config.ts`: Main Nuxt configuration with modules
- `package.json`: Scripts and dependencies
- `eslint.config.mjs`: ESLint configuration extending Nuxt defaults
- `tsconfig.json`: TypeScript configuration