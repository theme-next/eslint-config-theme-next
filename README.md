# eslint-config-theme-next

[![npm-image]][npm-url]
[![lic-image]](LICENSE)

[ESLint](https://www.github.com/eslint/eslint) config for projects under [theme NexT](https://github.com/theme-next) organization.

## Installation

![size-image]
[![dm-image]][npm-url]
[![dt-image]][npm-url]

There are two ways to install this configuration preset with `ESLint`: globally or locally.

### Global Installation (recommended)

```bash
npm install -g eslint
npm install -g eslint-config-theme-next
```

### Local Installation

```bash
npm install --save-dev eslint
npm install --save-dev eslint-config-theme-next
```

## Usage

If file `.eslintrc.json` not exists under needed repository, then need to create it:

```json
{
  "extends": "theme-next",
  "root": true
}
```

Then need to install ESLint plugin under your editor. For example, I use [Visual Studio Code](https://github.com/Microsoft/vscode/) with [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint) plugin installed.

[npm-image]: https://img.shields.io/npm/v/eslint-config-theme-next.svg?style=flat-square
[lic-image]: https://img.shields.io/npm/l/eslint-config-theme-next?style=flat-square

[size-image]: https://img.shields.io/github/languages/code-size/theme-next/eslint-config-theme-next?style=flat-square
[dm-image]: https://img.shields.io/npm/dm/eslint-config-theme-next?style=flat-square
[dt-image]: https://img.shields.io/npm/dt/eslint-config-theme-next?style=flat-square

[npm-url]: https://www.npmjs.com/package/eslint-config-theme-next
