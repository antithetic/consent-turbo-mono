# Consent Turbo Monorepo

This is a modern monorepo built with Turborepo, featuring multiple applications and shared packages. The project uses pnpm as the package manager and includes various tools for development efficiency.

## Project Structure

### Apps
- `web`: An [Astro](https://astro.build) application for the main web interface
- `docs`: A vanilla [Vite](https://vitejs.dev) TypeScript application for documentation

### Packages
- `@repo/ui`: Shared component & utility library
- `@repo/email`: Email-related utilities and templates
- `@repo/eslint-config`: Shared ESLint configurations
- `@repo/typescript-config`: Shared TypeScript configurations

## Technology Stack

- **Package Manager**: [pnpm](https://pnpm.io) (v8.15.6)
- **Build System**: [Turborepo](https://turbo.build) (v2.5.4)
- **Frontend Framework**: [Astro](https://astro.build) (v5.9.2)
- **Development Tools**:
  - [TypeScript](https://www.typescriptlang.org/) for static type checking
  - [ESLint](https://eslint.org/) for code linting
  - [Prettier](https://prettier.io) for code formatting

## Getting Started

1. Install dependencies:
```sh
pnpm install
```

2. Start development servers:
```sh
pnpm dev
```

3. Build all applications and packages:
```sh
pnpm build
```

## Available Scripts

- `pnpm dev` - Start all development servers
- `pnpm build` - Build all applications and packages
- `pnpm lint` - Run linting across all packages
- `pnpm format` - Format all TypeScript and Markdown files

## Development

This monorepo is set up with Turborepo for optimal development experience. Each package and app is 100% TypeScript-based, ensuring type safety across the entire project.

The project uses a workspace-based approach with pnpm, allowing for efficient dependency management and shared configurations across all packages.
