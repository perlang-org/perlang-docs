# README

> **No longer used**; superseded by https://github.com/perlun/perlang/tree/master/docs.

## Local development

Running the Hugo server locally:

```shell
$ hugo serve -D
```

Note that this will conveniently provide a hot-reloading web server. Whenever you change a Markdown document for the web page you are looking at in the web browser, the browser automatically refreshes the contents.

## Building the site

Since the `public/` folder [is a submodule](http://blog.blindgaenger.net/generate_github_pages_in_a_submodule.html), we can conveniently rebuild it and push the updated content to GitHub like this:

```shell
$ hugo
$ cd public/
$ git add .
$ git commit -m 'Rebuilt'
$ git push
```
