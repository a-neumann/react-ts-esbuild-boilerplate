# React TypeScript esbuild boilerplate

## Features

- local dev server with `npm start` script
- custom HTML template with envorinment variable injecting
- analyze bundle with `npm run analyze` script
- unit test setup with [Jest](https://jestjs.io), pre configured with [Testing Library](https://testing-library.com/) to test React components
- build script configured for long term caching with hashed output names
- configured for importing media files in CSS or TypeScript code 
- CSS entry point for global overrides and importing fonts files with [CSS imports](https://developer.mozilla.org/en-US/docs/Web/CSS/@import)
- copy script for serving static assets directory
- source maps and debug script for Visual Studio Code launching Firefox or Chrome supporting live-reload

## Motivation
- lightweight setup, 9 dev dependencies excluding types
- About 83MB dependencies instead of 310M in comparison to [Create React App](https://create-react-app.dev)
- plain template repository, easy to configure and extend

## Not included
Linting and code formatting is currently not included.

[Prettier](https://prettier.io) is not creating very readable code since blank lines after function signatures [is not supported](https://github.com/prettier/prettier/issues/4870).

[ESLint](https://eslint.org) may be added later when the compatibility of [typescript-eslint](https://typescript-eslint.io) is ready for version 9 that uses another configuration file format.
It is easily possible to install one or both of this tools on top of this template.