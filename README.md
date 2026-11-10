# PostCSS Feuille de Styles Française

[![travis](https://img.shields.io/travis/com/dakumisu/postcss-francais-feuille-de-styles.svg?style=flat-square)](https://app.travis-ci.com/github/dakumisu/postcss-francais-feuille-de-styles)
[![npm](https://img.shields.io/npm/v/postcss-francais-feuille-de-styles.svg?style=flat-square)](https://www.npmjs.com/package/postcss-francais-feuille-de-styles)

> [PostCSS](https://github.com/postcss/postcss) plugin for writing French Style Sheets.

Take CSS to the next level and write your CSS « à la française » 🇫🇷 !

## Installation

```console
$ npm install postcss-francais-feuille-de-styles
```

## Usage

```js
// ES5
var frenchStyleSheets = require('postcss-francais-feuille-de-styles')

// ES6
import frenchStyleSheets from 'postcss-francais-feuille-de-styles'
```

See [PostCSS#Usage](https://github.com/postcss/postcss#usage) for usage for your environment.

## Example

Using this `input.css`:

```css
.fou {
    hauteur: 300px;
    marge-du-bas: 10px;
    taille-de-la-typographie: 20px !prioritaire;
    couleur-du-fond: aiguemarine;
    couleur: blanc;
}
```

you will get:

```css
.fou {
    height: 300px;
    margin-bottom: 10px;
    font-size: 20px !important;
    background-color: aquamarine;
    color: white;
}
```

## Documentation

- [Properties](https://github.com/dakumisu/postcss-francais-feuille-de-styles/blob/master/docs/Properties.md)
- [Values](https://github.com/dakumisu/postcss-francais-feuille-de-styles/blob/master/docs/Values.md)

## Contributing

`postcss-francais-feuille-de-styles` has only a subset of CSS and needs your help to add more French properties and values.

## Changelog

See [CHANGELOG.md](https://github.com/dakumisu/postcss-francais-feuille-de-styles/blob/master/CHANGELOG.md).

## License

postCSS French CSS is based on the [postCSS German CSS](https://github.com/timche/postcss-german-stylesheets) plugin. Danke to them for the base architecture !

See [LICENSE](https://github.com/dakumisu/postcss-francais-feuille-de-styles/blob/master/LICENSE).
