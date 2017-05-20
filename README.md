# Stylelint Config Savvy

_Stylelint Configuration for Savvy CSS_

## Installation

With [`yarn`]():
```shell
yarn add --dev @savvy-css/stylelint-config-savvy
```

With [`npm`]():
```shell
npm install --save-dev @savvy-css/stylelint-config-savvy
```

## Usage

Simply _extend_ this configuration your own Stylelint configuration:

```js
{
  "extends": "stylelint-config-savvy"
}
```

### Extending the config

Simply add a `"rules"` key to your config and add your overrides there.

For example, to change the `indentation` to tabs and turn off the `number-leading-zero` rule:

```json
{
  "extends": "stylelint-config-suitcss",
  "rules": {
    "indentation": "tab",
    "number-leading-zero": null
  }
}
```

## [Changelog](CHANGELOG.md)

## [License](LICENSE)