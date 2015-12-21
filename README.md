# babel-preset-es2015-without-strict

> Babel preset for all es2015 plugins except CommonJS.

## Install

```sh
$ npm install --save-dev babel-preset-es2015-without-strict
```

## Usage

### Via `.babelrc` (Recommended)

**.babelrc**

```json
{
  "presets": ["es2015-without-strict"]
}
```

### Via CLI

```sh
$ babel script.js --presets es2015-without-strict 
```

### Via Node API

```javascript
require("babel-core").transform("code", {
  presets: ["es2015-without-strict"]
});
```
