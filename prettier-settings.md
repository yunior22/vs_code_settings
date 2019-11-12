# Prettier settings

Install dev dependecies:

```
yarn add -D prettier pretty-quick husky
```

Add the following to the end of package.json file

```
"prettier": {
    "printWidth": 120,
    "tabWidth": 2,
    "trailingComma": "all",
    "singleQuote": true,
    "semi": false,
    "jsxSingleQuote": true
  },
  "husky": {
    "hooks": {
      "pre-commit": "pretty-quick --staged"
    }
  }
```
