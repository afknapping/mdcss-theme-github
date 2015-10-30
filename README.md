# GitHub Theme

<img align="right" width="96" height="96" src="https://i.imgur.com/3rqeZXi.png" title="logo of mdcss">

[![NPM Version][npm-img]][npm]

[GitHub Theme] is a theme for [mdcss]. It is based on the documentation styles seen across GitHub.

## Usage

Add [mdcss] and [GitHub Theme] to your build tool:

```bash
npm install mdcss --save-dev
npm install mdcss-theme-github --save-dev
```

Whenever [mdcss] is used, reference this theme.

```js
require('mdcss')({
	theme: require('mdcss-theme-github')({ /* options */ })
})
```

## Options

#### `template`

Type: `String`  
Default: `'main'`

The template within the GitHub theme that you would like to use.

#### `index`

Type: `String`  
Default: `'index.html'`

The complete name of the main file that you would like generated inside the style guide directory.

[npm]:     https://www.npmjs.com/package/mdcss-theme-github
[npm-img]: https://img.shields.io/npm/v/mdcss-theme-github.svg
[mdcss]:   https://github.com/jonathantneal/mdcss

[GitHub Theme]: https://github.com/jonathantneal/mdcss-theme-github
