# GitHub Buttons

Showcase your GitHub (repo's) success with these static buttons featuring links to your GitHub repo or profile page and up-to-date watch, fork, and follower counts.

To get started, checkout <https://icey830.github.io/github-buttons/>!

## Bug tracker

Have a bug? Please create an issue here on GitHub at <https://github.com/icey830/github-buttons/issues>.

## Development

The GitHub buttons source code is split across three files in `src/`—the HTML, CSS, and JS—and compiled with [gulp](http://gulpjs.com).
The `github-btn.hml` file contains the button markup and includes the external CSS and JS. Those includes are inlined and the overall page minified with gulp.

To build the files, just run gulp:

```shell
$ gulp
```

Lastly, the `https://ghbtns.com` site is built with Jekyll (requires Ruby and more). Install [Jekyll](http://jekyllrb.com) and run a local server to view your changes:

```shell
$ jekyll serve --watch
```

## See also

- [icey830/github-buttons](https://icey830.github.io/github-buttons/)



