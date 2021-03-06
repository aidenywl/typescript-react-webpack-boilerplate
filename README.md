# Typescript Webpack React Boilerplate

A Typescript boilerplate repository with Typescript, Webpack, CSS Modules, and React Testing library set up to jump right into Typescript React development. Linting with `tslint` and `prettier` has also been set up.

I created this to serve as a boilerplate for frontend projects that come to mind in the future. Feel free to use it for any of your own projects!

## Getting Started

### Editor Set-up

1. Obtain the extensions:

- [Prettier](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode): Code formatter, configured via `.prettierrc`
- [TSLint](https://marketplace.visualstudio.com/items?itemName=ms-vscode.vscode-typescript-tslint-plugin): TS linter, configured via `.tslint.json`
- [Stylelint](https://marketplace.visualstudio.com/items?itemName=stylelint.vscode-stylelint): CSS linter, configured via `.stylelintrc`
- [PostCSS syntax](https://marketplace.visualstudio.com/items?itemName=ricard.PostCSS): Enable postCSS syntax to use Javascript variables inside CSS files.

2. Update workspace's `settings.json` with this:

   "editor.formatOnSave": true,

3. Reload your editor

### Running the starter page

1. Pull the repository
2. Run `yarn` to install all packages.
3. Run `yarn start` and go to your browser to see the starting website.

## What's included in the boilerplate?

### Development

- Typescript modules and all relevant react modules for development with typescript are installed.
- Webpack is configured to build and serve Typescript and CSS files.
- Babel is set up for ES6 syntax.
- CSS Loader and POSTCSS Loader is used to shift away from global css and localized css for each component.
- Further CSS set-up: `autoprefixer` and `autoprefixer` normalizes styles for each browser and takes away the trouble of writing specific css classes for each browser

### Testing Framework

- Jest is set up and ready to go via `yarn test`.
- React Testing Library is used to write tests instead of enzyme for flexibility and being able to better simulate the DOM as seen by a user.
- Using RTL allows us to move away from snapshot testing and test each component mocking components as required.
