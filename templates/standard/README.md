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
