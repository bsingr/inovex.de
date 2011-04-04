# inovex.de

A tryout to set the [inovex](http://inovex.de) web page to a different level in style, structure and geekness. The pages are generated using [jekyll](https://github.com/mojombo/jekyll) a static page generator. It is easy to extend and has a lot of good features build in. *jeykll* is the heart of github pages...

## Generate Page

Just staticly generate the page to the _\_site_ directory:

    $ jekyll

## Server

Start a server that is constantly watching the directory for changes and rebuild if a changed happend. It will serve all assets and emulate the production environment.

    $ jekyll --server 9000 --auto

## Compile SASS

Since we use [SASS](http://sass-lang.com/) to compile the stylesheets we need to start a watch daemon using this command:

    $ sass --watch style:stylesheets
