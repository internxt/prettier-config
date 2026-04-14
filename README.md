# @internxt/prettier-config

Prettier configuration for Internxt projects.

## Installation

```bash
npm install --save-dev @internxt/prettier-config
```

## Usage

### .prettierrc.js

```js
module.exports = {
  ...require("@internxt/prettier-config"),
};
```

## Current base configuration

| Option          | Value |
| --------------- | ----- |
| `printWidth`    | 120   |
| `tabWidth`      | 2     |
| `useTabs`       | false |
| `semi`          | true  |
| `singleQuote`   | true  |
| `trailingComma` | all   |
| `endOfLine`     | lf    |

## License

MIT
