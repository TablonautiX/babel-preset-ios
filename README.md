# babel-preset-ios

> Babel preset for Safari/iOS for version 9+.

## Install

```sh
$ npm install --save-dev babel-preset-ios
```

## Usage

### Via `.babelrc` (Recommended)

**.babelrc**

```json
{
  "presets": ["babel-preset-ios"]
}
```

### Via CLI

```sh
$ babel script.js --presets babel-preset-ios
```

### Via Node API

```javascript
require("babel-core").transform("code", {
  presets: ["babel-preset-ios"]
});
```
