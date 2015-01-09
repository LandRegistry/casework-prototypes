# Casework Prototypes
===================

Made with [Jekyll](http://jekyllrb.com/), [Bootstrap](http://getbootstrap.com/) & [Font Awesome](http://fortawesome.github.io/Font-Awesome/).

Tested with [HTML Proofer](https://github.com/gjtorikian/html-proofer).

Deployed by [Travis CI](https://travis-ci.org/matthew-shaw/matthew-shaw.github.io).

Hosted by [MaxCDN](http://www.bootstrapcdn.com/) and [GitHub Pages](https://pages.github.com/).

### Getting started
Requires [Ruby](https://www.ruby-lang.org/en/downloads/) and [RubyGems](http://rubygems.org/pages/download).
```
git clone git@github.com:LandRegistry/casework-prototypes.git
cd casework-prototypes
bundle install
bundle exec jekyll serve
```

### Running tests
This is the same script that Travis runs during the build, run this locally before pushing to avoid broken builds:
```
./script/cibuild
```
