# Prettier configuration

## Installation

```bash
npm install --save-dev @msg-labs/prettier-config
```

## Usage

You can use this prettier config by adding this to your `package.json`:

```json
{
    "prettier": "@msg-labs/prettier-config"
}
```

If you want to override any rule of the configuration, create a `.prettierrc.js` file with the following content:

```javascript
module.exports = {
    ...require('@msg-labs/prettier-config'),
    semi: false
};
```
