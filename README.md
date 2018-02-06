```
yarn add callbag-gamepad
```

```javascript
const pipe = require("callbag-pipe");
const forEach = require("callbag-for-each");
const gamepads = require("./index.js");

pipe(
  gamepads,
  forEach(gamepads => {
    // have fun
  })
);
```
