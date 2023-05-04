# Geta ESLint config

## Installation

```
yarn add --dev eslint prettier @geta-org/eslint-config
```

*Note: We're using `yarn` to install deps. Feel free to change commands to use `npm` 3+ and `npx` if you like*

## Usage

Create a `.eslintrc.json` file extending the config:

```json
{
    "extends": "@geta-org/eslint-config/native"
}
```

> You can also use a `.eslintrc.js` instead of JSON if you prefer.