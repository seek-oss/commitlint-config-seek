[![Build Status](https://img.shields.io/travis/seek-oss/commitlint-config-seek/master.svg?style=flat-square)](http://travis-ci.org/seek-oss/commitlint-config-seek) [![npm](https://img.shields.io/npm/v/commitlint-config-seek.svg?style=flat-square)](https://www.npmjs.com/package/commitlint-config-seek) [![semantic-release](https://img.shields.io/badge/%20%20%F0%9F%93%A6%F0%9F%9A%80-semantic--release-e10079.svg?style=flat-square)](https://github.com/semantic-release/semantic-release) [![Commitizen friendly](https://img.shields.io/badge/commitizen-friendly-brightgreen.svg?style=flat-square)](http://commitizen.github.io/cz-cli/)


# commitlint-config-seek

Shareable [commitlint](https://github.com/marionebl/commitlint) configuration for [SEEK](https://github.com/seek-oss).

This configuration uses the [conventional](https://github.com/marionebl/commitlint/tree/master/@commitlint/config-conventional) commit format, with a couple of exceptions:
- Scopes are case insensitive (rather than lower case), most notably to support React components, e.g. `fix(Button): ...`
- Subjects are sentence case (rather than lower case), because it (arguably) improves readability.

## Usage
You can set this up [a few different ways](https://github.com/marionebl/commitlint#config), easiest is probably just adding it into your `package.json` like so:

```js
{
  "commitlint": {
    "extends": "commitlint-config-seek"
  }
}
```

## License

MIT.
