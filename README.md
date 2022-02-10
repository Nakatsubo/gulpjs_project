# Simple Gulp4 Setting

## Install

```bash
$ npm init -y
$ npm install -D gulp browser-sync gulp-plumber gulp-notify gulp-sass sass gulp-postcss autoprefixer css-declaration-sorter gulp-sass-glob gulp-group-css-media-queries gulp-mode gulp-babel gulp-uglify-es gulp-sourcemaps webpack webpack-stream
```
## Command

```bash
// Javascript Task
// Compiled by Uglify
$ npx gulp

// Compiled by webpack
$ npx gulp bundle
```

### For Production

```javascript:gulpfile.js
// true -> false
src(GULP_PATHS.SRC_SASS, { sourcemaps: false  /* init */})
```

```javascript:webpack.config.js
// development -> production
mode: "production",
```
