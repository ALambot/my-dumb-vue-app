# my-dumb-vue-app

Demo on how to import and use **my-dumb-vue-lib**

## The important stuff :

- *npm install* the dependency *git+https://github.com/ALambot/my-dumb-vue-lib.git* (already defined in the package.json here)
- in your *main.js*, import the library style : *import './../node_modules/my-dumb-vue-lib/dist/style.css'*
- in your *App.vue* (or other Vue components), import and use the lib components : *import {OneDumbButton, ThreeDumbButtons} from 'my-dumb-vue-lib'*

## Recommended IDE Setup

[VSCode](https://code.visualstudio.com/) + [Volar](https://marketplace.visualstudio.com/items?itemName=Vue.volar) (and disable Vetur) + [TypeScript Vue Plugin (Volar)](https://marketplace.visualstudio.com/items?itemName=Vue.vscode-typescript-vue-plugin).

## Customize configuration

See [Vite Configuration Reference](https://vitejs.dev/config/).

## Project Setup

```sh
npm install
```

### Compile and Hot-Reload for Development

```sh
npm run dev
```

### Compile and Minify for Production

```sh
npm run build
```
