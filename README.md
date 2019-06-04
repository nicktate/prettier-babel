# prettier-configs
Shared [prettier](https://prettier.io) configurations for Containership.

## Usage

**Install**
```js
yarn add --dev @containership/prettier-configs
```

**Add to `package.json`**
```jsonc
{
  // ...existing package.json
  "prettier": "@containership/prettier-configs/<parser type>"
}
```

**Example `package.json` usage for Babel**
```jsonc
{
  // ...existing package.json
  "prettier": "@containership/prettier-configs/babel"
}
```
