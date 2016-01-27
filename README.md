# mocha-mix-jsdom-3

mocha-mix plugin to enable global `window` and `document` objects for server-side testing.
This plugin particularly uses jsdom@3.x, so that it can be run on node versions like
0.12.x, 0.10.x, ...and so on.

## Usage

```bash
npm install mocha-mix mocha-mix-jsdom-3 --save-dev
```

```js
var MochaMix = require('mocha-mix');
var JsdomPlugin = require('mocha-mix-jsom');

MochaMix.use(JsdomPlugin());

// or

JsdomPlugin();
```
