# Basic Monorepo

This is a basic monorepo for starters no extra layer just barebone for junior engineers

* **Add npm package to a local package/app**

  ```
  pnpm add --filter logger typescript

  ```
* **Build Logger package (Run from root)**

  ```
  pnpm --filter logger build

  ```
* **Add Logger as dependency(Run from root)**

  ```
  pnpm add ./packages/logger --workspace-root
  ```
* **Add local Logger as dependency to a project/app**

```
pnpm add @pnpmworkspace/logger --filter ui
```
