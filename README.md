[@vscodium/policy-watcher](https://github.com/VSCodium/policy-watcher)
======================================================================

[![Version](https://img.shields.io/npm/v/@vscodium/policy-watcher.svg)](https://npmjs.org/package/@vscodium/policy-watcher)

## <a id="usage"></a>Usage

```js
const createWatcher = require("@vscodium/policy-watcher");

createWatcher(
  // vendor name
  "VSCodium",
  // product name
  "VSCodium",
  {
    UpdateMode: { type: "string" },
    SCMInputFontSize: { type: "number" },
  },
  (update) => console.log(update)
);
```

## <a id="license"></a>License

[MIT](https://github.com/VSCodium/policy-watcher/blob/master/LICENSE)