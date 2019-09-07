# `tsconfig`

Base TypeScript configuration for frontend (i.e. browser based) projects. The config is meant to be used alongside Babel for suitability for Create React App based projects.

## Usage

`tsconfig.json`

```json
{
  "extends": "@chapabu/tsconfig-fe",
  "exclude": [
    "node_modules/*"
  ],
  "include": [
    "src"
  ]
}
```
