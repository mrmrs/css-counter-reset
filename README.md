# css-counter-reset 1.0.6

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

Learn more about using css installed with npm:
* https://webpack.github.io/docs/stylesheets.html
* https://github.com/defunctzombie/npm-css

#### With Git

http:
```
git clone https://github.com/tachyons-css/css-counter-reset
```

ssh:
```
git clone git@github.com:tachyons-css/css-counter-reset.git
```

## Usage

#### Using with [Postcss](https://github.com/postcss/postcss)

Import the css module

```css
@import "css-counter-reset";
```

Then process the css using the [`tachyons-cli`](https://github.com/tachyons-css/tachyons-cli)

```sh
$ npm i -g tachyons-cli
$ tachyons path/to/css-file.css > dist/t.css
```

#### Using the css

##### CDN
The easiest and most simple way to use the css is to use the cdn hosted version. Include it in the head of your html with:

```
<link rel="stylesheet" href="http://unpkg.com/css-counter-reset@1.0.6/css/css-counter-reset.min.css" />
```

##### Locally
The built css is located in the `css` directory. It contains an unminified and minified version.
You can either cut and paste that css or link to it directly in your html.

```html
<link rel="stylesheet" href="path/to/module/css/css-counter-reset">
```

#### Development

The source css files can be found in the `src` directory.
Running `$ npm start` will process the source css and place the built css in the `css` directory.

## The css

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

ISC

