# Multilingual Jekyll [![Build Status](https://travis-ci.org/sylvaindurand/multilingual-jekyll.svg?branch=gh-pages)](https://travis-ci.org/sylvaindurand/multilingual-jekyll)

This repository aims to show how to get a minimal multilingual *Jekyll* website.

It is based on the [**Making *Jekyll* multilingual**](https://www.sylvaindurand.org/making-jekyll-multilingual/) article, applied on the [Jekyll default theme](https://github.com/jglovier/jekyll-new).

You can check the demo on [multilingual.sylvaindurand.org](https://multilingual.sylvaindurand.org/).

## Make your website multilingual

1. Have a look at the article [Making *Jekyll* multilingual](https://www.sylvaindurand.org/making-jekyll-multilingual/), which explains how things work
2. Check the [diff for Jekyll 3.1.2](https://github.com/sylvaindurand/multilingual-jekyll/commit/111495e91e8986db21368e54a42188cdbbc44b6f) (older versions: [3.0.0](https://github.com/sylvaindurand/multilingual-jekyll/commit/b2da2a07c325a1b6e01f524dad6582f2daf70ccf), [2.5.3](https://github.com/sylvaindurand/multilingual-jekyll/commit/e0bed79df22d2d35a75d0906e2c9c2baeac44a73))
3. Reproduce it on your website!

## Create a multilingual website from stratch

1. Still have a look at the article [Making *Jekyll* multilingual](https://www.sylvaindurand.org/making-jekyll-multilingual/), which explains how things work
2. Clone the repo: `git clone https://github.com/sylvaindurand/multilingual-jekyll.git`
3. Open the folder: `cd multilingual-jekyll`
4. Remove `Readme.md`, `CNAME` and `.travis.yml`, which are useless outside this repository
5. Install the dependencies: `gem install jekyll` (with *Ruby*)
6. Build the website: `jekyll serve`
7. Look at [localhost:4000](http://localhost:4000): surprise!

## Colophon

After having written an article about having a multilingual *Jekyll* website, [sigul](https://talk.jekyllrb.com/t/a-vanilla-jekyll-theme-multilingual-with-no-plugins/) gave the idea to provide a minimal working example. Here we are!

The [source code](https://github.com/sylvaindurand/multilingual-jekyll) is freely available on [GitHub](https://github.com/sylvaindurand/multilingual-jekyll). The *Jekyll* default theme is released under the MIT License, such as the modifications shown in this repository.

## Question?
Please feel free to [open an issue](https://github.com/sylvaindurand/multilingual-jekyll/issues) or to [push a commit](https://github.com/sylvaindurand/multilingual-jekyll/pulls).
