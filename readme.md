gulpfile-jshintrc
=================

My Standard Gulpfile + the needed .jshintrc

The Dependencies to get this running.

    $ npm install gulp-ruby-sass gulp-autoprefixer gulp-minify-css gulp-jshint gulp-concat gulp-uglify gulp-imagemin gulp-notify gulp-rename gulp-livereload gulp-cache del --save-dev

run ```gulp``` and after that ```gulp watch```.

It will automatically open a livereload server that can communicate with the browser plugin. And it will watch the files in the dev folder. After it detects a change it will run the tasks and reload the browser.

If you have to clear the dist folder you could run ```gulp clean```.
