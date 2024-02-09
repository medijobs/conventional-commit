<div align="center">
  <img src="https://gist.githubusercontent.com/0-vortex/acffcb296295f5d6e10865528ed5c7f2/raw/3666f45755d249534f83d5658ac892c6bc0b4963/medirecruit.svg" width="400">
</div>

# @medijobs/conventional-commit

> Never miss a conventional commit with [**commitizen**](https://github.com/commitizen/cz-cli) running on [**npx**](https://www.npmjs.com/package/npx).

[![Commits](https://img.shields.io/github/commit-activity/w/medijobs/conventional-commit?style=flat)](https://github.com/medijobs/conventional-commit/pulse)
[![Issues](https://img.shields.io/github/issues/medijobs/conventional-commit.svg?style=flat)](https://github.com/medijobs/conventional-commit/issues)
[![Releases](https://img.shields.io/github/v/release/medijobs/conventional-commit.svg?style=flat)](https://github.com/medijobs/conventional-commit/releases)

</div>

## 📦 Install

This package is binary and doesn't require installation however you can add it to your repository as a `devDependency`:

```shell
npm install --save-dev @medijobs/conventional-commit
```

## 🚀 Usage

All you have to do is run the script next to your `package.json`:

```shell
npx @medijobs/conventional-commit
# or
npx conventional-commit
```

## 🔧 Configuration

The most common use case for this package is to run it instead of the `git commit` command inside your `npm` scripts:

```json
{
  "scripts": {
    "push": "npx @medijobs/conventional-commit"
  }
}
```

or

```json
{
  "scripts": {
    "push": "npx conventional-commit"
  }
}
```

If you want to ensure local-only usage:

```json
{
  "scripts": {
    "push": "conventional-commit"
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
