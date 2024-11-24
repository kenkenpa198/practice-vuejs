# Practice - Vue.js - quick-start-with-playwright

## Setup commands

```shell
$ npm create vue@latest

> npx
> create-vue


Vue.js - The Progressive JavaScript Framework

RangeError: Incorrect locale information provided

✔ Project name: … quick-start
✔ Add TypeScript? … No / Yes # No
✔ Add JSX Support? … No / Yes # No
✔ Add Vue Router for Single Page Application development? … No / Yes # No
✔ Add Pinia for state management? … No / Yes # No
✔ Add Vitest for Unit Testing? … No / Yes # No
✔ Add an End-to-End Testing Solution? › Playwright # Yes -> Playwright
✔ Add ESLint for code quality? › No # No

Scaffolding project in /home/kenkenpa198/works/develop/practice-vuejs/src/quick-start...

Done. Now run:

  cd quick-start
  npm install
  npm run dev
```

---


# quick-start-with-playwright

This template should help get you started developing with Vue 3 in Vite.

## Recommended IDE Setup

[VSCode](https://code.visualstudio.com/) + [Volar](https://marketplace.visualstudio.com/items?itemName=Vue.volar) (and disable Vetur).

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

### Compile and Minify for Production

```sh
npm run build
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
