# JFrog / GitHub / Azure Boards Integration

This repo was forked from https://github.com/yonarbel/su2024

## Related Resources

- **Azure DevOps Team Project:**
  - [Dashboard](https://dev.azure.com/daveburnisonms/DemoJFrogIntegration/_dashboards/dashboard/4fd72b49-cb34-4124-b1b4-00d588b33605)
  - [Kanban Board](https://dev.azure.com/daveburnisonms/20e9f5e7-095d-4a16-b5a7-ab629eac49cd/_boards/board/t/7dabdfbe-7b7a-4163-b798-3be24e2ce8e0/Stories/)
- **GitHub Repo:** [https://github.com/devrellabs/DemoJFrogIntegration](https://github.com/devrellabs/DemoJFrogIntegration)
- **JFrog Artifactory Builds**: [GHJFIntegration](https://ghdevrel.jfrog.io/ui/builds/?projectKey=ghjfintegration&type=builds)

## Recommended IDE Setup

[VSCode](https://code.visualstudio.com/) + [Volar](https://marketplace.visualstudio.com/items?itemName=Vue.volar) (and disable Vetur).

## Customize configuration

See [Vite Configuration Reference](https://vitejs.dev/config/).

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
