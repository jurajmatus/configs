# Usage

## ESLint

Install the config of your choice, eslint and prettier:

```bash
yarn add -D eslint prettier
# one of
yarn add -D https://gitpkg.now.sh/jurajmatus/configs/packages/eslint-config-...
```

Add this to `.eslintrc.json`:

```diff
{
-  "extends": [],
+  "extends": ["@jurajmatus/eslint-config-..."],
}
```

## Prettier

Create `.prettierrc.js`:

```js
const prettierBase = require("@jurajmatus/prettier-config");
module.exports = prettierBase;
```
