# [textventure.github.io](https://textventure.github.io/)

[Site](https://textventure.github.io/) of [@textventure](https://github.com/textventure). Built with [Jekyll](https://jekyllrb.com/) and hosted on [GitHub Pages](https://pages.github.com/).

## Prerequisites

[Ruby](https://www.ruby-lang.org/en/downloads/) 2.6.0:

```sh
$ ruby --version
```

If your version is behind, you can either install ruby with [rbenv](https://github.com/rbenv/rbenv) or [RVM](https://rvm.io/).

To install and set up rbenv on macOS:

```sh
$ brew install rbenv
$ rbenv init
# restart or open a new shell
$ curl -fsSL https://github.com/rbenv/rbenv-installer/raw/master/bin/rbenv-doctor | bash
$ rbenv install 2.6.0
$ rbenv local 2.6.0
```

And [Bundler](http://bundler.io/):

```sh
$ gem install bundler
$ bundler --version
```

## Installation

Clone the repository:

```sh
$ git clone --recursive https://github.com/textventure/textventure.github.io.git
$ cd $_
```

Install dependencies:

```sh
$ bundle install
```

## Update

Update dependencies:

```sh
$ git checkout master
$ git pull
$ bundle update
```

## Run

### Development Server

```sh
$ bundle exec jekyll serve --livereload # --incremental
```

The server will be running at http://127.0.0.1:4000/:

```sh
$ open http://127.0.0.1:4000/
```

Press `CTRL-C` to stop the server.

### Production Build

```sh
$ bundle exec jekyll build
```

The site will be generated at `./_site/`.
