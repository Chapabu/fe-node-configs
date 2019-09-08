# `tsconfig`

Base TypeScript configuration shared between FE and Node TSConfig files.

## Usage

You probably don't want to use this by itself. But if you do...

`npm install @chapabu/tsconfig-base`  or `yarn add @chapabu/tsconfig-base`

`tsconfig.json`

```json
{
  "extends": "@chapabu/tsconfig-base",
  "include": [
    "src"
  ]
}
```
