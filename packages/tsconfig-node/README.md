# `tsconfig`

Base TypeScript configuration for Node projects.

Targets ES2018 for full compatibility with Node 10.

## Usage

`npm install @chapabu/tsconfig-node`  or `yarn add @chapabu/tsconfig-node`

`tsconfig.json`

```json
{
  "extends": "@chapabu/tsconfig-node",
  "include": [
    "src"
  ]
}
```

### I want to use Node 8

Just swap out the target in your project's `tsconfig.json`.

`tsconfig.json`

```json
{
  "extends": "@chapabu/tsconfig-node",
  "compilerOptions": {
    "target": "es2017",
    "lib": ["es2017"]
  },
  "include": [
    "src"
  ]
}
```
