# Prettier



## Install

```sh
npm install eslint prettier eslint-config-prettier eslint-plugin-prettier -D
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
    "plugin:prettier/recommended"
  ],
  "parserOptions": {
    "ecmaVersion": "latest",
    "sourceType": "module"
  }
}
```

`.prettierrc.json`

```json
{
  "printWidth": 160,
  "semi": true,
  "singleQuote": true,
  "endOfLine": "auto",
  "trailingComma": "none"
}
```
