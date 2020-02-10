# Webpack 4 + Typescript Boilerplate

Pre-configured Webpack 4 boilerplate using Typescript and additional loaders for fast development. 

Top dependencies:

- [ts-loader](https://github.com/TypeStrong/ts-loader)
- [style-loader](https://github.com/webpack-contrib/style-loader)
- [sass-loader](https://github.com/webpack-contrib/sass-loader)
- [loadash](https://github.com/lodash/lodash-webpack-plugin)

## Software Requirements

- [NodeJS](https://nodejs.org/es/)
- [Yarn](https://yarnpkg.com/lang/en/) (optional)
- [Webpack](https://webpack.js.org/)
- [TypeScript](https://www.typescriptlang.org/)

## Install

First install dependencies:

```sh
npm install
```

## Build

To create a production build:

```sh
npm run build-prod
```

To create a development build:

```sh
npm run build-dev
```

## Run

```sh
node dist/bundle.js
```

## Folder structure

```
├── dist
└── src
    ├── index.ts
    └── ...
```

- `dist`: Final .js distribution files
- `src`:  App source code
- `index.ts`:  Main project file. 

