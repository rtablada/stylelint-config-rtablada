# stylelint-config-rtablada
[![NPM version](http://img.shields.io/npm/v/stylelint-config-rtablada.svg)](https://www.npmjs.org/package/stylelint-config-rtablada) [![Travis Build Status](https://img.shields.io/travis/rtablada/stylelint-config-rtablada/master.svg?label=unix%20build)](https://travis-ci.org/rtablada/stylelint-config-rtablada)

> SuitCSS shareable config for stylelint.

My CSS style guide is very similar to the [SuitCSS's code style](https://github.com/suitcss/suit/blob/master/doc/STYLE.md)
with one change in that I find that CSS rules should be grouped logically instead of alphabetically.

## Installation

```console
$ npm install stylelint-config-rtablada
```

## Usage

Set your stylelint config to:

```json
{
  "extends": "stylelint-config-rtablada"
}
```

### Extending the config

Simply add a `"rules"` key to your config and add your overrides there.

For example, to change the `indentation` to tabs and turn off the `number-leading-zero` rule:


```json
{
  "extends": "stylelint-config-rtablada",
  "rules": {
    "indentation": [2, "tab"],
    "number-leading-zero": 0
  }
}
```

## [Changelog](CHANGELOG.md)

## [License](LICENSE)
