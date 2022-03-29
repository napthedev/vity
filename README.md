<p align="center">
  <img width="600" src="https://res.cloudinary.com/naptest/image/upload/v1648526872/vity-cli_qlxsmo.png">
</p>

# Vity

[![Version](https://img.shields.io/npm/v/vity?style=flat&color=success)](https://www.npmjs.com/package/vity)
[![Downloads](https://img.shields.io/npm/dt/vity.svg?style=flat&color=success)](https://www.npmjs.com/package/vity)

CLI based on Vite to generate your project easily

## Feature

- ⚛️ Support React, Vue, Svelte
- 🖥 Typescript support
- 📖 Less boilerplate
- ⏰ Always up to date dependencies
- ⚙️ Choose your own tool / framework you need
  - Tailwind
  - Sass
  - Router (react-router-dom, vue-router, svelte-navigator)
  - ESLint
  - Prettier
  - Unit test (Vitest)

## Get started

```bash
npx vity
```

## Examples

Name your project

```bash
npx vity my-app
```

Generate your project in the current working directory

```bash
npx vity .
```

Specify a template: react, react-ts, vue, vue-ts, svelte, svelte-ts

```bash
npx vity --template react
```

Use yarn to install packages

```bash
npx vity --with-yarn
```
