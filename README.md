# Spaceboot

## Requirements

- Node.js version 22.14.x
- PNPM version 8.15.0 or higher

This project is configured to work exclusively with PNPM as the package manager. NPM and Yarn are intentionally disabled.

## Getting Started

1. Install Node.js 22.14.x:
   ```bash
   # Using nvm (recommended)
   nvm install 22.14.0
   nvm use 22.14.0
   ```

2. Install PNPM:
   ```bash
   corepack enable
   corepack prepare pnpm@8.15.0 --activate
   ```

3. Install dependencies:
   ```bash
   pnpm install
   ```

4. Start the development server:
   ```bash
   pnpm start
   ```

## Scripts

- `pnpm start` - Start the application in development mode
- `pnpm package` - Package the application
- `pnpm make` - Make platform-specific distributables
- `pnpm publish` - Publish the application
- `pnpm lint` - Run ESLint

## Note

This project enforces the use of PNPM and Node.js 22.14.x through engine constraints. Using other package managers or Node.js versions will result in errors. 