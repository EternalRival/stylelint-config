# @eternalrival/stylelint-config

Stylelint [sharing configuration](https://stylelint.io/user-guide/configure#extends)

## Using a Shareable Config

### Installation

```sh
npm install -D @eternalrival/stylelint-config
```

### Usage

You can extend it in your `stylelint.config.mjs`

```js
/** @type {import('stylelint').Config} */
const config = {
  extends: ['@eternalrival/stylelint-config'],
};

export default config;
```
