# @tapp-group/prettier-config

TAPP Group Prettier Configs

## Install

```bash
yarn add --dev @tapp-group/prettier-config
```

## Usage

Create `prettier.config.js`:

```js
module.exports = require('@tapp.group/prettier-config')
```

For alternative methods, see [Prettier Docs](https://prettier.io/docs/en/configuration.html#sharing-configurations)

### Extending configuration

Edit `prettier.config.js`:

```js
module.exports = {
  ...require('@tapp.group/prettier-config'),
  printWidth: 120,
}
```

## Example

See `package.json` for commands: `format` and `format:check`

Recommeneded to ignore `package.json`, see `.prettierignore`.
