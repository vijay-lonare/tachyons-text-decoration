# tachyons-text-decoration 3.1.2

Performance based css module.

#### Stats

203 | 12 | 12
---|---|---
bytes | selectors | declarations

## Installation

#### With [npm](https://npmjs.com)

```
npm install --save-dev tachyons-text-decoration
```

#### With Git

```
git clone https://github.com/tachyons-css/tachyons-text-decoration
```

## Usage

#### Using with [PostCSS](https://github.com/postcss/postcss)

Import the css module

```css
@import "tachyons-text-decoration";
```

Then process the CSS using the [`tachyons-cli`](https://github.com/tachyons-css/tachyons-cli)

```sh
$ npm i -g tachyons-cli
$ tachyons path/to/css-file.css > dist/t.css
```

#### Using the CSS

The built CSS is located in the `css` directory. It contains an unminified and minified version.
You can either cut and paste that css or link to it directly in your html.

```html
<link rel="stylesheet" href="path/to/module/css/tachyons-text-decoration">
```

#### Development

The source CSS files can be found in the `src` directory.
Running `$ npm start` will process the source CSS and place the built CSS in the `css` directory.

## The CSS

```css
/*

   TEXT DECORATION

*/
.strike { text-decoration: line-through; }
.underline { text-decoration: underline; }
.no-underline { text-decoration: none; }
@media screen and (min-width: 48em) {
 .strike-ns { text-decoration: line-through; }
 .underline-ns { text-decoration: underline; }
 .no-underline-ns { text-decoration: none; }
}
@media screen and (min-width: 48em) and (max-width: 64em) {
 .strike-m { text-decoration: line-through; }
 .underline-m { text-decoration: underline; }
 .no-underline-m { text-decoration: none; }
}
@media screen and (min-width: 64em) {
 .strike-l { text-decoration: line-through; }
 .underline-l { text-decoration: underline; }
 .no-underline-l { text-decoration: none; }
}
```

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request

## Authors

* [mrmrs](http://mrmrs.io)
* [johno](http://johnotander.com)

## License

MIT

