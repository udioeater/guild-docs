# Pillar Guild Handbook

This handbook is built on top of [Jekyll](http://jekyllrb.com/)

### Notes

As a reminder, in order for changes to be visible, all changes need to be within the **`gh-pages`** branch.

Reference for github pages - http://jekyllrb.com/docs/github-pages/

Docs for development - https://help.github.com/articles/using-jekyll-with-pages/

### Contributions

If you find anything wrong or would like to contribute in any way, feel free to

* create a pull request,
* open an issue, or
* send us a message.

Any and all comments are welcome!

### Running locally

First, make sure you have Ruby 2.x and bundler installed. Follow [these instructions](https://help.github.com/articles/setting-up-your-github-pages-site-locally-with-jekyll/#requirements) if not. Also you'll need a local clone of the repo.

Then, run `bundle install` (from the base directory of the repo) to download and install Jekyll and its dependencies.

To build the site and start a local server, run:

```
bundle exec jekyll serve --baseurl '/guild-docs'
```
and you'll get Jekyll running locally on port 4000. Access it from your browser at [http://localhost:4000/guild-docs/](). When making changes, Jekyll will automatically rebuild when you save a file. Just reload your browser to see the latest version.

Another option, to take advantage of the dev configuration, is to run the following:

```
bundle exec jekyll serve --config _config.yml,_config_dev.yml
```
This will load the two config files and override values in the first one with values from the second.
