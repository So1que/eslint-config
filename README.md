# so1que/eslint-config

## About config

- This is the base config for eslint based on the `airbnb-base` config but modernized and supported

## Installation
- You need to install `@so1que/eslint-config` into the project as `devDependencies`

```bash
npm i -D so1que/eslint-config
```

## Usage
- An example of how to use the config:

```ts
module.exports = {
    extends: ["@so1que/eslint-config"]
}
```

- If you use multiple configs in `extends`, `@so1que/eslint-config` should be left as the last element of the array because it overrides the base rules