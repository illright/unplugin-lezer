# unplugin-lezer

[![NPM version](https://img.shields.io/npm/v/unplugin-lezer?color=a1b858&label=)](https://www.npmjs.com/package/unplugin-lezer)

Universal plugin to import [Lezer](https://lezer.codemirror.net/) grammar files.

## Install

```bash
npm i unplugin-lezer
```

<details>
<summary>Vite</summary><br>

```ts
// vite.config.ts
import lezer from 'unplugin-lezer/vite'

export default defineConfig({
  plugins: [
    lezer(),
  ],
})
```

Example: [`playground/`](./playground/)

<br></details>

<details>
<summary>Rollup</summary><br>

```ts
// rollup.config.js
import lezer from 'unplugin-lezer/rollup'

export default {
  plugins: [
    lezer(),
  ],
}
```

<br></details>


<details>
<summary>Webpack</summary><br>

```ts
// webpack.config.js
module.exports = {
  /* ... */
  plugins: [
    require('unplugin-lezer/webpack')()
  ]
}
```

<br></details>

<details>
<summary>Vue CLI</summary><br>

```ts
// vue.config.js
module.exports = {
  configureWebpack: {
    plugins: [
      require('unplugin-lezer/webpack')(),
    ],
  },
}
```

<br></details>

<details>
<summary>esbuild</summary><br>

```ts
// esbuild.config.js
import { build } from 'esbuild'
import lezer from 'unplugin-lezer/esbuild'

build({
  plugins: [lezer()],
})
```

<br></details>
