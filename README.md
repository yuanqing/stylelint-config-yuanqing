# stylelint-config-yuanqing [![npm Version](https://img.shields.io/npm/v/stylelint-config-yuanqing?cacheSeconds=1800)](https://www.npmjs.com/package/stylelint-config-yuanqing)

> An opinionated [Stylelint](https://stylelint.io/) configuration

## Features

- Auto-formatting with [Prettier](https://prettier.io/)
- Auto-sorting of properties following a [rational order](https://github.com/constverum/stylelint-config-rational-order/blob/master/README.md#stylelint-config-rational-order)

## Usage

Install:

```
$ npm install --save-dev prettier@3 stylelint@16
$ npm install --save-dev --save-exact stylelint-config-yuanqing
```

Then, update `package.json` as follows:

```json
{
  "scripts": {
    "fix-css": "stylelint --fix 'src/**/*.css'",
    "lint-css": "stylelint 'src/**/*.css'"
  },
  "stylelint": {
    "extends": "stylelint-config-yuanqing"
  }
}
```

## License

[MIT](LICENSE.md)
