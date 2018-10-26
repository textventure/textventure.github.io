# [textventure.github.io](https://textventure.github.io/)

Site of [textventure](https://textventure.github.io/). Built with [Jekyll](https://jekyllrb.com/) and hosted on [GitHub Pages](https://pages.github.com/).

## Requirements

You need [Ruby](https://www.ruby-lang.org/en/downloads/) 2.1.0 or higher:

```sh
$ ruby --version
```

And [Bundler](http://bundler.io/):

```sh
# gem install bundler
$ bundler --version
```

## Installation

Clone the repository:

```sh
$ git clone --recursive https://github.com/textventure/textventure.github.io.git
$ cd textventure.github.io
```

Then install gem dependencies:

```sh
$ bundle install
```

## Update

You should update your gem dependencies from time-to-time:

```sh
# git checkout master
$ git pull
$ bundle update
```

## Run

### Development server

```sh
$ bundle exec jekyll serve --livereload # --incremental
```

The server will be running at [`http://127.0.0.1:4000/`](http://127.0.0.1:4000/).

Press `CTRL-C` to stop the server.

### Production build

```sh
$ bundle exec jekyll build
```

Your site will be generated at `./_site/`.
