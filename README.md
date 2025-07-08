# webpack-eslint-prettier-template

A starter template for modern JavaScript projects using **Webpack**, **ESLint**, **Prettier**, **Husky**, and **lint-staged**.

## Features

- **Webpack** for bundling assets
- **ESLint** for code linting
- **Prettier** for code formatting
- **Husky** for Git hooks
- **lint-staged** for running linters on staged files

## Getting Started

### Installation

```bash
npm install
```

### Development

Start the development server:

```bash
npm run dev
```

### Production Build

Build the project for production:

```bash
npm run build
```

### Linting

Run ESLint on your code:

```bash
npm run lint
```

### Pre-commit Hook

On commit, `lint-staged` will automatically lint and format your staged files using ESLint and Prettier.

## Customization

- Update `.prettierrc` to configure Prettier.
- Update `eslint.config.mjs` to configure ESLint rules.
