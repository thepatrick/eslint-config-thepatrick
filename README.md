# eslint-config-opentok

This package provides [thepatrick][0]'s .eslintrc as an extensible shared config.

[0]: https://github.com/thepatrick

## Usage

We export two ESLint configurations for your usage.

### eslint-config-thepatrick

Lints ES6+. Requires `eslint` and `babel-eslint`.

1. `npm install --save-dev eslint-config-thepatrick eslint babel-eslint`
2. add `"extends": "thepatrick"` to your .eslintrc

### eslint-config-thepatrick/es5

Lints ES5 and below. Only requires `eslint`.

1. `npm install --save-dev eslint-config-thepatrick eslint`
2. add `"extends": "thepatrick"` to your .eslintrc


1. `npm install --save-dev eslint-config-thepatrick babel-eslint eslint`
2. add `"extends": "opentok/es6"` to your .eslintrc


## Changelog

### 1.0.0

Welcome!
