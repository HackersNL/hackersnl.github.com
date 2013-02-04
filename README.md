BEEA website
============

This is the website of [BEEA](http://www.beea.nl). Contributing is encouraged. Just fork the website,
hack and create a pull request.

Hacking
-------

The site runs on [Jekyll](http://jekyllrb.com/) and is hosted on Github pages. This means the site
must stay vanilla Jekyll compatible otherwise Github Pages can't render it.

You can use [Bundler](http://gembundler.com/) to install all the dependencies (`bundle install`). 
If you don't have Bundler and want to install the gems yourself, check the Gemfile for a complete list.

`jekyll --server` starts a webserver on localhost:4000 with the site. This allows you to preview
changes locally before submitting them.
