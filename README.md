# demo-jekyll

## How to run

clone repository

```sh
https://github.com/hochun836/demo-jekyll.git
cd demo-jekyll
```

install `ruby >= 2.4.0` (recommend by `rvm`)

```sh
rvm get master

rvm install 2.4.0
```

install `bundler`

```sh
gem install bundler
```

install dependency

```sh
bundle install
```

start server (default localhost:4000)

```sh
bundle exec jekyll serve

or

bundle exec jekyll s
```

make broswer auto reload

```sh
bundle exec jekyll serve --livereload

or

bundle exec jekyll serve
(set livereload: true in _config.yml)
```

build code (default output _site)

```sh
bundle exec jekyll build

or

bundle exec jekyll b
```
