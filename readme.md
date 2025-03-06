<div align="center">

  <a href="https://github.com/fivefifteen/growfield">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="./assets/growfield-white.png">
      <img src="./assets/growfield.png" alt="GrowField">
    </picture>
  </a>

  # GrowField

  A tiny, dependency-free JavaScript module for making textarea elements grow with their content.

  [![npm package version](https://img.shields.io/npm/v/growfield.svg?style=flat-square)](https://www.npmjs.com/package/growfield)
  [![npm package downloads](https://img.shields.io/npm/dt/growfield.svg?style=flat-square)](https://www.npmjs.com/package/growfield)
  [![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/fivefifteen/growfield?style=flat-square)](https://github.com/fivefifteen/growfield)
  [![code style](https://img.shields.io/badge/code_style-standard-yellow.svg?style=flat-square)](https://github.com/standard/standard)
  [![license](https://img.shields.io/github/license/fivefifteen/growfield.svg?style=flat-square)](license.md)

  <a href="https://fivefifteen.com" target="_blank"><img src="./assets/fivefifteen.png" /><br /><b>A Five Fifteen Project</b></a>

</div>


## Demo

Visit https://growfield.js.org


## Installation


### Manual Download

Download [dist/growfield.min.js](dist/growfield.min.js) and place the following HTML in your page's head element:

```html
<script type="text/javascript" src="dist/growfield.min.js"></script>
```


### CDN (Courtesy of [jsDelivr](https://jsdelivr.com))

Place the following HTML in your page's head element (check to make sure the version in the URL is the version you want):

```html
<script type="text/javascript" src="https://cdn.jsdelivr.net/gh/fivefifteen/growfield@0.1/dist/growfield.min.js"></script>
```


### [NPM](https://npmjs.com)

```
npm install growfield --save
```

```js
// ES6
import growfield from 'growfield'

// CommonJS
const growfield = require('growfield')
```


### [Fetcher](https://github.com/fivefifteen/fetcher)

```
fetcher install fivefifteen/growfield --save
```


### [Bower](https://bower.io)

```
bower install fivefifteen/growfield --save
```


## Usage

### `growfield` Function

`growfield([selector], [options])`

Initializes GrowField.


#### Parameters

 - `selector` (Optional) - A query string for textareas that you would like to use growfield on.

 - `options` (Optional) - An object of options.


#### Examples

```js
window.addEventListener('load', function () {
  growfield()
})
```


#### Options

```js
{
  maxRows: null, // The maximum number of rows to grow the field to before normal scrolling happens
  minRows: null  // The minimum number of rows to start with (Defaults to 1)
}
```


## Credit

A special thanks to Rick Kukiela for posting [this StackOverflow answer](https://stackoverflow.com/a/73226649/5463842) which is where the base code of this module came from.


## Related

 - [ColorTap](https://github.com/fivefifteen/colortap) - A tiny, dependency-free, color input field helper that utilizes the native color picker.

 - [FileBokz](https://github.com/fivefifteen/filebokz) - A tiny, dependency-free, highly customizable and configurable, easy to use file input with some pretty sweet features.

 - [HashJump](https://github.com/fivefifteen/hashjump) - A tiny, dependency-free JavaScript module for handling anchor links and scrolling elements into view.

 - [Kloner](https://github.com/fivefifteen/kloner) - A tiny, dependency-free JavaScript module for cloning/repeating elements.


## License

MIT. See the [license file](license.md) for more info.