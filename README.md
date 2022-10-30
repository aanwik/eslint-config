# @aanwik/eslint-config

Prettier and ESlint configuration I use for the majority of react projects. It is based on airbnb config with some rules tweaks.

## Installation

```sh
npx install-peerdeps --dev @aanwik/eslint-config
```

## Usage

Example usage (see [mayavi](https://github.com/aanwik/mayavi) for full usage):

```js
// .eslintrc.js
module.exports = {
  extends: ['@aanwik/eslint-config'],
  rules: {
    /* override rules */
  },
};

// .prettierrc.js
module.exports = require('@aanwik/eslint-config/.prettierrc');
```
