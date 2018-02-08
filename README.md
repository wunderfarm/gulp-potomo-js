# gulp-potomo-js [![Build Status](https://travis-ci.org/wunderfarm/gulp-potomo-js.svg?branch=master)](https://travis-ci.org/wunderfarm/gulp-potomo-js)

A Gulp plugin to compile .po files into binary .mo files written in JavaScript only.

---

## Requirements
* This plugin requires Gulp


## Install

```shell
npm install --save-dev gulp-potomo-js
```


## Usage

```js
const gulp = require('gulp');
const poToMo = require('gulp-potomo-js');

gulp.task('default', () =>
	gulp.src('src/languages/*.po')
		.pipe(poToMo())
		.pipe(gulp.dest('dist/languages'))
);
```


### Options

No options at the moment.


## License

MIT © [wunderfarm](https://www.wunderfarm.com)
