# CSS COUNTER RESET

  Mobile-first classes for css-counter-reset.
  Set the desired css-counter-reset on any element for any breakpoint.
  Base class names are namespaced across three breakpoints:

*  -ns = not-small (covers everything larger than mobile)
*  -m  = medium
*  -l  = large

## Install
Grab the css partial from github and include it in your project or alternatively
you can install it via npm:
```
npm install --save-dev css-counter-reset
```
View on [npm](https://www.npmjs.org/package/css-counter-reset)


## File Size

813B counter-reset.css
614B counter-reset.min.css
177B minified and gzipped

## The Code
```
.cr {       counter-reset: count; }
.cr-minus { counter-reset: count -1; }
.cr-none {  counter-reset: none; }
.cr-i {     counter-reset: inherit; }

@media screen and (min-width: 48em) {
  .cr-ns {       counter-reset: count; }
  .cr-minus-ns { counter-reset: count -1; }
  .cr-none-ns {  counter-reset: none; }
  .cr-i-ns {     counter-reset: inherit; }
}

@media screen and (min-width: 48em) and (max-width: 64em) {
  .cr-m {       counter-reset: count; }
  .cr-minus-m { counter-reset: count -1; }
  .cr-none-m {  counter-reset: none; }
  .cr-i-m {     counter-reset: inherit; }
}

@media screen and (min-width: 64em)  {
  .cr-l {       counter-reset: count; }
  .cr-minus-l { counter-reset: count -1; }
  .cr-none-l {  counter-reset: none; }
  .cr-i-l {     counter-reset: inherit; }
}

```

## Author

[http://mrmrs.cc - Entire internet gateway to all things mrmrs](http://mrmrs.cc)
[http://mrmrs.io - Open source projects](http://mrmrs.io)

## License

The MIT License (MIT)

Copyright (c) 2015 @mrmrs

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.

