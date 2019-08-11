var gulp = require('gulp');
var autoprefixer = require('gulp-autoprefixer');

gulp.task('styles', function() {
    gulp.src('/sass/style.scss')
    .pipe(autoprefixer())
    .pipe(gulp.dest('/css/style.css'));
});




VS Code: 


{
    "workbench.iconTheme": "vscode-great-icons",
    "window.zoomLevel": 0,
    "editor.suggestSelection": "first",
    "vsintellicode.modify.editor.suggestSelection": "automaticallyOverrodeDefaultValue",
    "liveSassCompile.settings.formats": [
        {
            "format": "expanded",
            "extensionName": ".css",
            "savePath": "/css"
        }
    ]
}
