# PrestaShop Build

Official blog for PrestaShop development straight from the product and core dev team.

https://build.prestashop.com

## About

This devblog is where the PrestaCrew communicates directly with the community. It's especially targeted at those who contribute (Core, translations, documentation, modules/themes, etc.)

It is about everything that has to do with PrestaShop development. The whole PrestaShop product team contributes: developers, product managers, designers, tech writers, etc. [We welcome your contributions](#contribute)!

We write about everything that happens to the PrestaShop software:

* New releases,
* Code activity in the past week,
* The upcoming improvement in the codebase, 
* Current and future architectures, 

...and all behavior changes that might affect you as a developer, a module/theme author, or simply as a Open Source fan :)

This devblog also hosts How-Tos on certain features, before they find their way in the Developer Guide or the Designer Guide.

## Run locally

build.prestashop.com is built and hosted by [GitHub Pages](https://github.com/github/pages-gem) which leverages [Jekyll](https://jekyllrb.com/) (a Ruby static site generator) abilities.

We recommend using Ruby 3.1

### Setup

```bash
$ gem install bundler
$ bundle install
```

### Run local server

```bash
$ bundle exec jekyll serve
```

Blog should be available at [http://127.0.0.1:4000/](http://127.0.0.1:4000/)

## Contribute

How about writing a guest post here? Maybe you've been working with PrestaShop for a while and you want to write about how you use it? Or you feel a cool feature could use a highlight with sample code? Go ahead, [suggest a new article](http://build.prestashop.com/howtos/misc/how-to-write-on-this-blog/) — that might even inspire other people in the community to write too!

Before you start writing, please send us a short proposal by opening a GitHub issue. Once we have agreed with you on the topic, you can submit your article [using a simple pull request](https://github.com/PrestaShop/prestashop.github.io).

Also, if we merge one of your cool pull requests on [the PrestaShop project](http://github.com/PrestaShop/PrestaShop), we may invite you to tell us more about it here.

All content on the Build.PrestaShop.com site is licensed under the [CC0 license](https://creativecommons.org/publicdomain/zero/1.0/) -- meaning that it is in the Public Domain. Use it however you want!

<img src="/assets/images/2015/06/cc-zero.png" style="margin-right:auto;margin-left:auto;display:block;" />

## Guidelines

**Support**

This blog is not for support. If you need help, you can search [our forum](http://www.prestashop.com/forums) or open a new thread there.

**Feature requests**

If you want to see some feature added to PrestaShop, please open an 'Improvement' ticket on [Github](https://github.com/PrestaShop/PrestaShop/issues/new?template=feature_request.md).

**Bug report**

If you find a bug or something that doesn't work as expected, please open a 'Bug' ticket on [Github](https://github.com/PrestaShop/PrestaShop/issues/new?template=bug_report.md).
