# @bunstormjs/tsconfig

<hr>
<br />

<div align="center">
  <h3>Base TSConfig files</h3>
  <p>TSConfig config files for BunStorm (including Inertia) applications or BunStorm packages.</p>
</div>

<br />

<div align="center">

[![npm-image]][npm-url] [![license-image]][license-url]

</div>

## Installation

Install the package from the npm registry.

```sh
npm i -D @bunstormjs/tsconfig
```

## Usage

After installation, use one of the following base config files.

**For package development**

```json
// tsconfig.json
{
  "extends": "@bunstormjs/tsconfig/tsconfig.package.json",
  "compilerOptions": {
    "rootDir": "./",
    "outDir": "./build"
  }
}
```

**For BunStorm application**

```json
// tsconfig.json
{
  "extends": "@bunstormjs/tsconfig/tsconfig.app.json",
  "compilerOptions": {
    "rootDir": "./",
    "outDir": "./build"
  }
}
```

**For client-side code inside BunStorm application**

```ts
// resources/tsconfig.json
{
  "extends": "@bunstormjs/tsconfig/tsconfig.client.json"
}
```

<div align="center">
  <sub>Built with ❤︎ by <a href="https://github.com/sayeed205">Sayed Ahmed</a>
</div>

[npm-image]: https://img.shields.io/npm/v/@bunstormjs/tsconfig/latest.svg?style=for-the-badge&logo=npm
[npm-url]: https://www.npmjs.com/package/@bunstormjs/tsconfig/v/latest 'npm'
[license-url]: LICENSE.md
[license-image]: https://img.shields.io/github/license/bunstormjs/tsconfig?style=for-the-badge
