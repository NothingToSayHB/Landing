var gulp = require('gulp');
var autoprefixer = require('gulp-autoprefixer');

gulp.task('styles', function() {
    gulp.src('/sass/style.scss')
    .pipe(autoprefixer())
    .pipe(gulp.dest('/css/style.css'));
});
