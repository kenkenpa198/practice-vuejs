# Practice - Vue.js - quick-start-with-all

## Setup commands

```shell
$ npm create vue@latest

> npx
> create-vue


Vue.js - The Progressive JavaScript Framework

RangeError: Incorrect locale information provided

✔ Project name: … quick-start-with-all
✔ Add TypeScript? … No / Yes # Yes
✔ Add JSX Support? … No / Yes # No
✔ Add Vue Router for Single Page Application development? … No / Yes # No
✔ Add Pinia for state management? … No / Yes # Yes
✔ Add Vitest for Unit Testing? … No / Yes # Yes
✔ Add an End-to-End Testing Solution? › Playwright # Yes
✔ Add ESLint for code quality? › Yes # Yes
✔ Add Prettier for code formatting? … No / Yes # Yes

Scaffolding project in /home/kenkenpa198/works/develop/practice-vuejs/packages/quick-start-with-all...

Done. Now run:

  cd quick-start-with-all
  npm install
  npm run format
  npm run dev
```

---

# quick-start-with-all

This template should help get you started developing with Vue 3 in Vite.

## Recommended IDE Setup

[VSCode](https://code.visualstudio.com/) + [Volar](https://marketplace.visualstudio.com/items?itemName=Vue.volar) (and disable Vetur).

## Type Support for `.vue` Imports in TS

TypeScript cannot handle type information for `.vue` imports by default, so we replace the `tsc` CLI with `vue-tsc` for type checking. In editors, we need [Volar](https://marketplace.visualstudio.com/items?itemName=Vue.volar) to make the TypeScript language service aware of `.vue` types.

## Customize configuration

See [Vite Configuration Reference](https://vite.dev/config/).

## Project Setup

```sh
npm install
```

### Compile and Hot-Reload for Development

```sh
npm run dev
```

### Type-Check, Compile and Minify for Production

```sh
npm run build
```

### Run Unit Tests with [Vitest](https://vitest.dev/)

```sh
npm run test:unit
```

### Run End-to-End Tests with [Playwright](https://playwright.dev)

```sh
# Install browsers for the first run
npx playwright install

# When testing on CI, must build the project first
npm run build

# Runs the end-to-end tests
npm run test:e2e
# Runs the tests only on Chromium
npm run test:e2e -- --project=chromium
# Runs the tests of a specific file
npm run test:e2e -- tests/example.spec.ts
# Runs the tests in debug mode
npm run test:e2e -- --debug
```

### Lint with [ESLint](https://eslint.org/)

```sh
npm run lint
```
