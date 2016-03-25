# Pillar Guild Handbook 

This handbook is built on top of [Jekyll](http://jekyllrb.com/)

### Notes

As a reminder, in order for changes to be visible, all changes need to be within the '**gh-pages**' branch.

Reference for github pages - http://jekyllrb.com/docs/github-pages/

Docs for development - https://help.github.com/articles/using-jekyll-with-pages/

### Contributions

If you find anything wrong or would like to contribute in any way, feel free to 

* create a pull request,
* open an issue, or 
* send us a message.

Any and all comments are welcome!

### Running locally

Once you have followed the instructions above, a simple " bundle install " and  " bundle 
exec jekyll serve --baseurl '/guild-docs' " will get Jekyll running locally on port 4000

Another option, to take advantage of the dev configuration, is to run the following:
" bundle exec jekyll serve --config _config.yml,_config_dev.yml "
This will load the two config files and override values in the first one with values from the second.
