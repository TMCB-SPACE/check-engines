<div align="center">
  <img src="https://gist.githubusercontent.com/0-vortex/3ba0d05bcd4afdbd0f2bf20542caf682/raw/02c432297a6822cd2944a41b9cc9986357d49748/His_Worshipful_Grace-1.svg" width="400">

# @tmcb/check-engines

> Never break your dependency tree with [**npm-install-checks**](https://www.npmjs.com/package/npm-install-checks) running on [**npx**](https://www.npmjs.com/package/npx).

[![Commits](https://img.shields.io/github/commit-activity/w/TMCB-SPACE/check-engines?style=flat)](https://github.com/TMCB-SPACE/check-engines/pulse)
[![Issues](https://img.shields.io/github/issues/TMCB-SPACE/check-engines.svg?style=flat)](https://github.com/TMCB-SPACE/check-engines/issues)
[![Releases](https://img.shields.io/github/v/release/TMCB-SPACE/check-engines.svg?style=flat)](https://github.com/TMCB-SPACE/check-engines/releases)

</div>

## 📦 Install

This package is binary and doesn't require installation however you can add it to your repository as a `devDependency`:

```shell
npm install --save-dev @tmcb/check-engines
```

## 🚀 Usage

All you have to do is run the script next to your `package.json`:

```shell
npx @tmcb/check-engines
```

## 🔧 Configuration

The most common use case for this package is to let it run on `install` and `start` generic `npm` scripts:

```json
{
  "scripts": {
    "preinstall": "npx @tmcb/check-engines",
    "prestart": "npx @tmcb/check-engines"
  }
}
```

Or with less copy paste:

```json
{
  "scripts": {
    "engines": "npx @tmcb/check-engines",
    "preinstall": "npm run engines",
    "prestart": "npm run engines"
  }
}
```

## 🤝 Contributing

If you decide to fix a bug, make sure to use the conventional commit available at:

```shell
npm run push
```

## ⚖️ LICENSE

MIT © [TED (Teodor-Eugen Dutulescu) Vortex](./LICENSE)
