# Standard



## Install

```sh
npm install eslint standard eslint-config-standard -D
```



## Configuration

`.eslintrc.json`

```json
{
  "root": true,
  "env": { 
    "es6": true
  },
  "extends": [
    "standard"
  ],
  "parserOptions": {
    "ecmaVersion": "latest",
    "sourceType": "module"
  }
}
```



## TypeScript

install

```sh
npm install typescript @typescript-eslint/parser @typescript-eslint/eslint-plugin eslint-config-standard-with-typescript -D
```

`.eslintrc.json`

```json
{
  "root": true,
  "env": { 
    "es6": true
  },
  "plugins": [
    "@typescript-eslint"
  ],
  "extends": [
    "standard-with-typescript"
  ],
  "parser": "@typescript-eslint/parser",
  "parserOptions": {
    "ecmaVersion": "latest",
    "sourceType": "module",
    "project": "./tsconfig.ts"
  }
}
```

`tsconfig.ts`

```ts
export default {
  compilerOptions: {
    strictNullChecks: true
  }
}
```
