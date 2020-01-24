# eslint-config
A set of standard eslint rules to use on Typescript repositories

## Getting Started

Install the package:
```sh
npm install --save-dev @libero/eslint-config
```

Or using yarn:

```sh
yarn add --dev @libero/eslint-config
```

In your package root, create an `.eslintrc.js` file with following contents:

```js
module.exports = {
  "extends": "@libero/eslint-config"
}
```

You should now be able to run `yarn lint` with the inherited rules.