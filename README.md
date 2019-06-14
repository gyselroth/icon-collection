# SVG icon collection
[![npm](https://img.shields.io/npm/v/@gyselroth/icon-collection.svg)](https://www.npmjs.com/package/@gyselroth/icon-collection)
[![GitHub release](https://img.shields.io/github/release/gyselroth/icon-collection.svg)](https://github.com/gyselroth/icon-collection/releases)
[![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)](https://raw.githubusercontent.com/gyselroth/icon-collection/master/LICENSE)

This library provides an icon collection based on svg.

## Installation
```
npm --save install @gyselroth/icon-collection
```

## Documentation & Overview

Please visit the [docs](https://gyselroth.github.io/icon-collection/).

## Usage example
```html
<div class="gr-icon gr-i-file"></div>
```

## Colorize your icons

You can use an icon with any color you like. If you do you have to switch from the css class `gr-icon` to `gr-mask-icon`.
An icon with gr-mask-icon takes the color from `background-color`.

```html
<div style="background-color: #F01;" class="gr-mask-icon gr-i-file"></div>
```

### Browser Support
If you want to use color masks, please see browser support for [css masks](http://caniuse.com/#feat=css-masks).
