# Standard



## Install

npm

```sh
npm install standard eslint-config-standard eslint eslint-plugin-import eslint-plugin-node eslint-plugin-promise -D
```

yarn

```sh
yarn add standard eslint-config-standard eslint eslint-plugin-import eslint-plugin-node eslint-plugin-promise -D
```



## Configuration

`.eslintrc.json`

```json
{
  "root": true,
  "env": { 
    "es6": true
  },
  "extends": ["standard"],
  "parserOptions": {
    "ecmaVersion": 2020,
    "sourceType": "module"
  }
}
```



## TypeScript

npm

```sh
npm install eslint typescript @typescript-eslint/parser @typescript-eslint/eslint-plugin eslint-config-standard-with-typescript -D
```

yarn

```sh
yarn add eslint typescript @typescript-eslint/parser @typescript-eslint/eslint-plugin eslint-config-standard-with-typescript -D
```

`.eslintrc.json`

```json
{
  "root": true,
  "env": { 
    "es6": true
  },
  "plugins": ["@typescript-eslint"],
  "extends": ["standard-with-typescript"],
  "parser": "@typescript-eslint/parser",
  "parserOptions": {
    "ecmaVersion": 2020,
    "sourceType": "module",
    "project": "./tsconfig.json"
  }
}
```

`tsconfig.json`

```json
{
  "compilerOptions": {
    "strictNullChecks": true
  }
}
```
