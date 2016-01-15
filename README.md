# css-counter-reset 0.0.7

Css module of single purpose classes for counter reset

#### Stats

207 | 16 | 16
---|---|---
bytes | selectors | declarations

## Installation

#### With [npm](https://npmjs.com)

```
npm install --save-dev css-counter-reset
```

#### With Git

```
git clone https://github.com/tachyons-css/css-counter-reset
```

## Usage

#### Using with [PostCSS](https://github.com/postcss/postcss)

Import the css module

```css
@import "css-counter-reset";
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
<link rel="stylesheet" href="path/to/module/css/css-counter-reset">
```

#### Development

The source CSS files can be found in the `src` directory.
Running `$ npm start` will process the source CSS and place the built CSS in the `css` directory.

## The CSS

```css
/*
   COUNTER RESET
*/
.cr { counter-reset: count; }
.cr-minus { counter-reset: count -1; }
.cr-none { counter-reset: none; }
.cr-i { counter-reset: inherit; }
@media screen and (min-width: 48em) {
 .cr-ns { counter-reset: count; }
 .cr-minus-ns { counter-reset: count -1; }
 .cr-none-ns { counter-reset: none; }
 .cr-i-ns { counter-reset: inherit; }
}
@media screen and (min-width:48em) and (max-width: 64em) {
 .cr-m { counter-reset: count; }
 .cr-minus-m { counter-reset: count -1; }
 .cr-none-m { counter-reset: none; }
 .cr-i-m { counter-reset: inherit; }
}
@media screen and (min-width: 64em) {
 .cr-l { counter-reset: count; }
 .cr-minus-l { counter-reset: count -1; }
 .cr-none-l { counter-reset: none; }
 .cr-i-l { counter-reset: inherit; }
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

