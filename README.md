# CSS TEXT RENDERING

  Mobile-first classes for css-text-rendering.
  Set the desired css-text-rendering on any element for any breakpoint.
  Base class names are namespaced across three breakpoints:

*  -ns = not-small (covers everything larger than mobile)
*  -m  = medium
*  -l  = large

## Install
Grab the css partial from github and include it in your project or alternatively
you can install it via npm:
```
npm install --save-dev css-text-rendering
```
View on [npm](https://www.npmjs.org/package/css-text-rendering)


## File Size

1.2K text-rendering.css
969B text-rendering.min.css 
229B minified and gzipped

## The Code
```
.txtr-auto      { text-rendering: auto; }
.txtr-speed     { text-rendering: optimizeSpeed; }
.txtr-legibile  { text-rendering: optimizeLegibility; }
.txtr-precise   { text-rendering: geometricPrecision; }
.txtr-i         { text-rendering: inherit; }

@media screen and (min-width: 48em) {
  .txtr-auto-ns      { text-rendering: auto; }
  .txtr-speed-ns     { text-rendering: optimizeSpeed; }
  .txtr-legibile-ns  { text-rendering: optimizeLegibility; }
  .txtr-precise-ns   { text-rendering: geometricPrecision; }
  .txtr-i-ns         { text-rendering: inherit; }
}

@media screen and (min-width: 48em) and (max-width: 64em) {
  .txtr-auto-m      { text-rendering: auto; }
  .txtr-speed-m     { text-rendering: optimizeSpeed; }
  .txtr-legibile-m  { text-rendering: optimizeLegibility; }
  .txtr-precise-m   { text-rendering: geometricPrecision; }
  .txtr-i-m         { text-rendering: inherit; }
}

@media screen and (min-width: 64em)  {
  .txtr-auto-l      { text-rendering: auto; }
  .txtr-speed-l     { text-rendering: optimizeSpeed; }
  .txtr-legibile-l  { text-rendering: optimizeLegibility; }
  .txtr-precise-l   { text-rendering: geometricPrecision; }
  .txtr-i-l         { text-rendering: inherit; }
}
```

## Author

[http://mrmrs.cc - Entire internet gateway to all things mrmrs](http://mrmrs.cc)
[http://mrmrs.io - Open source projects](http://mrmrs.io)

## License

The MIT License (MIT)

Copyright (c) 2014 @mrmrs

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

