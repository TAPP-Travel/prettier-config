# @tapp-group/prettier-config

TAPP Group Prettier Configs

## Install

```bash
yarn add --dev @tapp-group/prettier-config
```

## Usage

Add to `package.json`:

```json
{
  "prettier": "@tapp.group/prettier-config"
}
```

### Extending configuration

Create `.prettierrc.js` or `prettier.config.js`:

```js
module.exports = {
  ...require("@tapp.group/prettier-config"),
  semi: true
};
```
