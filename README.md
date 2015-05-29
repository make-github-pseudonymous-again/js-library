[js-library](http://aureooms.github.io/js-library)
==

All kinds of code bricks for JavaScript

[![NPM license](http://img.shields.io/npm/l/aureooms-js-library.svg?style=flat)](https://raw.githubusercontent.com/aureooms/js-library/master/LICENSE)
[![NPM version](http://img.shields.io/npm/v/aureooms-js-library.svg?style=flat)](https://www.npmjs.org/package/aureooms-js-library)
[![Bower version](http://img.shields.io/bower/v/aureooms-js-library.svg?style=flat)](http://bower.io/search/?q=aureooms-js-library)
[![Build Status](http://img.shields.io/travis/aureooms/js-library.svg?style=flat)](https://travis-ci.org/aureooms/js-library)
[![Coverage Status](http://img.shields.io/coveralls/aureooms/js-library.svg?style=flat)](https://coveralls.io/r/aureooms/js-library)
[![Dependencies Status](http://img.shields.io/david/aureooms/js-library.svg?style=flat)](https://david-dm.org/aureooms/js-library#info=dependencies)
[![devDependencies Status](http://img.shields.io/david/dev/aureooms/js-library.svg?style=flat)](https://david-dm.org/aureooms/js-library#info=devDependencies)
[![Code Climate](http://img.shields.io/codeclimate/github/aureooms/js-library.svg?style=flat)](https://codeclimate.com/github/aureooms/js-library)
[![NPM downloads per month](http://img.shields.io/npm/dm/aureooms-js-library.svg?style=flat)](https://www.npmjs.org/package/aureooms-js-library)
[![GitHub issues](http://img.shields.io/github/issues/aureooms/js-library.svg?style=flat)](https://github.com/aureooms/js-library/issues)
[![Inline docs](http://inch-ci.org/github/aureooms/js-library.svg?branch=master&style=shields)](http://inch-ci.org/github/aureooms/js-library)

Can be managed through [jspm](https://github.com/jspm/jspm-cli),
[duo](https://github.com/duojs/duo),
[component](https://github.com/componentjs/component),
[bower](https://github.com/bower/bower),
[ender](https://github.com/ender-js/Ender),
[jam](https://github.com/caolan/jam),
[spm](https://github.com/spmjs/spm),
and [npm](https://github.com/npm/npm).

## Install

### jspm
```terminal
jspm install github:aureooms/js-library
# or
jspm install npm:aureooms-js-library
```
### duo
No install step needed for duo!

### component
```terminal
component install aureooms/js-library
```

### bower
```terminal
bower install aureooms-js-library
```

### ender
```terminal
ender add aureooms-js-library
```

### jam
```terminal
jam install aureooms-js-library
```

### spm
```terminal
spm install aureooms-js-library --save
```

### npm
```terminal
npm install aureooms-js-library --save
```

## Require
### jspm
```js
let library = require( "github:aureooms/js-library" ) ;
// or
import library from 'aureooms-js-library' ;
```
### duo
```js
let library = require( "aureooms/js-library" ) ;
```

### component, ender, spm, npm
```js
let library = require( "aureooms-js-library" ) ;
```

### bower
The script tag exposes the global variable `library`.
```html
<script src="bower_components/aureooms-js-library/js/dist/library.min.js"></script>
```
Alternatively, you can use any tool mentioned [here](http://bower.io/docs/tools/).

### jam
```js
require( [ "aureooms-js-library" ] , function ( library ) { ... } ) ;
```