# SolidStart Template with TypeScript and Scss Modules

Everything you need to build a Solid project, powered by [`solid-start`](https://start.solidjs.com);

## Developing

Once you've created a project and installed dependencies with `npm install` (or `pnpm install` or `yarn`), start a development server:

```bash
npm run dev

# or start the server and open the app in a new browser tab
npm run dev -- --open
```

## Building

Solid apps are built with _adapters_, which optimise your project for deployment to different environments.

By default, `npm run build` will generate a Node app that you can run with `npm start`. To use a different adapter, add it to the `devDependencies` in `package.json` and specify in your `vite.config.js`.

## IDE Setup

### SCSS Intellisense
Name: Sass

VS Marketplace Link: https://marketplace.visualstudio.com/items?itemName=Syler.sass-indented

### SCSS (modern features) Intellisense
Name: Some Sass: extended support for SCSS and SassDoc

VS Marketplace Link: https://marketplace.visualstudio.com/items?itemName=SomewhatStationery.some-sass

### Imported SCSS Module in JS Intellisense:
Name: CSS Modules

VS Marketplace Link: https://marketplace.visualstudio.com/items?itemName=clinyong.vscode-css-modules