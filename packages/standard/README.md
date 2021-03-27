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
    "sourceType": "module"
  }
}
```
