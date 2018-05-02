# Contributing to NodeSchool Algiers

## Development

We use [Jekyll](https://jekyllrb.com/) to build [http://nodeschool.io/algiers](http://nodeschool.io/algiers). If you want to run the site or develop it locally you'll have to install the gems in our Gemfile:

```sh
bundle install --path=.gems
bundle exec jekyll build
```

Note, this is the same set of commands used by Travis.

### Generating the Site

A local development server can be started by running:

```sh
bundle exec jekyll serve
```


