# [gulp](http://gulpjs.com)-[pleeease](https://github.com/iamvdo/pleeease/) [![Build Status](https://secure.travis-ci.org/danielhusar/gulp-pleeease.svg?branch=master)](http://travis-ci.org/danielhusar/gulp-pleeease)

Gulp plugin for [pleeease](https://github.com/iamvdo/pleeease/)

See [pleeease](https://github.com/iamvdo/pleeease/) for documentation.

## Install

```
npm install --save-dev gulp-pleeease
```

## Example

```
var gulp = require('gulp');
var please = require('gulp-please');

gulp.task('screens', function () {
  gulp.src('./public/*.css')
  .pipe(please(options))
  .pipe(rename({
    suffix: '.min',
    extname: '.css'
  }))
  .pipe(gulp.dest('./public/'));
});

```

## options

same as [pleeease](https://github.com/iamvdo/pleeease/#options)


## License

MIT © [Daniel Husar](https://github.com/danielhusar)