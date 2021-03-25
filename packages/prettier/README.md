# Prettier

## Install

npm

```sh
npm install prettier eslint-config-prettier eslint-plugin-prettier -D
```

yarn

```sh
yarn add prettier eslint-config-prettier eslint-plugin-prettier -D
```

## Configuration

`.eslintrc.json`

```json
{
  "root": true,
  "env": { 
    "es6": true
  },
  "extends": ["plugin:prettier/recommended"],
  "parserOptions": {
    "sourceType": "module"
  }
}
```

`.prettierrc.json`

```json
{
  "printWidth": 160,
  "semi": false,
  "singleQuote": true,
  "endOfLine": "auto",
  "trailingComma": "none"
}
```
