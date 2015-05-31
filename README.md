Gulp JSModule (AMD) reconciler plugin
===================
Gulp plugin for reconciling AMD dependency trees in JavaScript projects.
###Installation &nbsp;  [![npm version](https://badge.fury.io/js/gulp-jsmodule.svg)](http://badge.fury.io/js/gulp-jsmodule)
```sh
npm install gulp-jsmodule
```
###Simple Usage
```javascript
var jsmodule = require("gulp-jsmodule");

/**
 * Build JS
 */
gulp.task('js', function () {
  gulp.src(['./src/**/*.js'])
    .pipe(jsmodule('out.js'))
    .pipe(gulp.dest('./dist/'));
});
```

