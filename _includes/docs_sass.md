For its CSS files, the browser is using [Sass](http://sass-lang.com/) with [Compass](http://compass-style.org/). If you want to update the browser stylesheet you should use theese two preconfigured Compass make target:

 * `make compass-compile` to compile in one run all Sass files
 * `make compass-watch` to compile all Sass files on each update

 You always need to run `make compass-compile` before commiting changes.
