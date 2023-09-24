<!--BEGIN HEADER-->
<div id="top" align="center">
  <h1>@autossey/tsconfig</h1>
  <a href="https://npmjs.com/package/@autossey/tsconfig">
    <img alt="npm" src="https://img.shields.io/npm/v/@autossey/tsconfig.svg">
  </a>
  <a href="https://github.com/AutosseyAI/tsconfig">
    <img alt="typescript" src="https://img.shields.io/github/languages/top/AutosseyAI/tsconfig.svg">
  </a>
</div>

<br />

<blockquote align="center">A base TSConfig for various project types.</blockquote>

<br />

_If I should maintain this repo, please ⭐️_
<a href="https://github.com/AutosseyAI/tsconfig">
  <img align="right" alt="GitHub stars" src="https://img.shields.io/github/stars/AutosseyAI/tsconfig?label=%E2%AD%90%EF%B8%8F&style=social">
</a>

_DM me on [Twitter](https://twitter.com/bconnorwhite) if you have questions or suggestions._
<a href="https://twitter.com/bconnorwhite">
  <img align="right" alt="Twitter Follow" src="https://img.shields.io/twitter/url?label=%40bconnorwhite&style=social&url=https%3A%2F%2Ftwitter.com%2Fbconnorwhite">
</a>

---
<!--END HEADER-->

## Install

<details open>
  <summary>
    <a href="https://www.npmjs.com/package/@autossey/tsconfig">
      <img src="https://img.shields.io/badge/npm-CB3837?logo=npm&logoColor=white" alt="NPM" />
    </a>
  </summary>

```sh
npm install --save-dev @autossey/tsconfig
```

</details>

<details open>
  <summary>
    <a href="https://yarnpkg.com/package/@autossey/tsconfig">
      <img src="https://img.shields.io/badge/yarn-2C8EBB?logo=yarn&logoColor=white" alt="Yarn" />
    </a>
  </summary>

```sh
yarn add --dev @autossey/tsconfig
```

</details>

<details open>
  <summary>
    <img src="https://img.shields.io/badge/pnpm-F69220?logo=pnpm&logoColor=white" alt="PNPM" />
  </summary>

```sh
pnpm add --save-dev @autossey/tsconfig
```

</details>

<details open>
  <summary>
    <img src="https://img.shields.io/badge/bun-EE81C3?logo=bun&logoColor=white" alt="Bun" />
  </summary>

```sh
bun add --dev @autossey/tsconfig
```

</details>

## Usage

In your `tsconfig.json` file:

### Bun
```json
{
  "extends": "@autossey/tsconfig/bun"
}
```

### DOM
```json
{
  "extends": "@autossey/tsconfig/dom"
}
```

### Next.js
```json
{
  "extends": "@autossey/tsconfig/next"
}
```

### Node
```json
{
  "extends": "@autossey/tsconfig/node"
}
```

### Node 18
```json
{
  "extends": "@autossey/tsconfig/node-18"
}
```

<!--BEGIN FOOTER-->

<br />

<h2 id="dependencies">Dependencies<a href="https://www.npmjs.com/package/@autossey/tsconfig?activeTab=dependencies"><img align="right" alt="dependencies" src="https://img.shields.io/librariesio/release/npm/@autossey/tsconfig.svg"></a></h2>

- [@types/node](https://www.npmjs.com/package/@types/node): TypeScript definitions for Node.js
- [bun-types](https://www.npmjs.com/package/bun-types): Type definitions for Bun, an incredibly fast JavaScript runtime

<br />

<h3>Dev Dependencies</h3>

- [jsonlint](https://www.npmjs.com/package/jsonlint): Validate JSON

<br />

<h2 id="license">License <a href="https://opensource.org/licenses/MIT"><img align="right" alt="license" src="https://img.shields.io/npm/l/@autossey/tsconfig.svg"></a></h2>

[MIT](https://opensource.org/licenses/MIT)
<!--END FOOTER-->
