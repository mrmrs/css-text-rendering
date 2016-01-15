# css-text-rendering 0.0.6

Css module of single purpose classes for text rendering

#### Stats

264 | 20 | 20
---|---|---
bytes | selectors | declarations

## Installation

#### With [npm](https://npmjs.com)

```
npm install --save-dev css-text-rendering
```

#### With Git

```
git clone https://github.com/tachyons-css/css-text-rendering
```

## Usage

#### Using with [PostCSS](https://github.com/postcss/postcss)

Import the css module

```css
@import "css-text-rendering";
```

Then process the CSS using the [`tachyons-cli`](https://github.com/tachyons-css/tachyons-cli)

```sh
$ npm i -g tachyons-cli
$ tachyons-cli path/to/css-file.css > dist/t.css
```

#### Using the CSS

The built CSS is located in the `css` directory. It contains an unminified and minified version.
You can either cut and paste that css or link to it directly in your html.

```html
<link rel="stylesheet" href="path/to/module/css/css-text-rendering">
```

#### Development

The source CSS files can be found in the `src` directory.
Running `$ npm start` will process the source CSS and place the built CSS in the `css` directory.

## The CSS

```css
/*
   TEXT RENDERING
*/
.txtr-auto { text-rendering: auto; }
.txtr-speed { text-rendering: optimizeSpeed; }
.txtr-legibile { text-rendering: optimizeLegibility; }
.txtr-precise { text-rendering: geometricPrecision; }
.txtr-i { text-rendering: inherit; }
@media screen and (min-width: 48em) {
 .txtr-auto-ns { text-rendering: auto; }
 .txtr-speed-ns { text-rendering: optimizeSpeed; }
 .txtr-legibile-ns { text-rendering: optimizeLegibility; }
 .txtr-precise-ns { text-rendering: geometricPrecision; }
 .txtr-i-ns { text-rendering: inherit; }
}
@media screen and (min-width:48em) and (max-width: 64em) {
 .txtr-auto-m { text-rendering: auto; }
 .txtr-speed-m { text-rendering: optimizeSpeed; }
 .txtr-legibile-m { text-rendering: optimizeLegibility; }
 .txtr-precise-m { text-rendering: geometricPrecision; }
 .txtr-i-m { text-rendering: inherit; }
}
@media screen and (min-width: 64em) {
 .txtr-auto-l { text-rendering: auto; }
 .txtr-speed-l { text-rendering: optimizeSpeed; }
 .txtr-legibile-l { text-rendering: optimizeLegibility; }
 .txtr-precise-l { text-rendering: geometricPrecision; }
 .txtr-i-l { text-rendering: inherit; }
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

