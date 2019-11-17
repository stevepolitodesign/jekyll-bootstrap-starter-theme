# Jekyll Bootstrap Starter Theme

This theme makes no other assumptions other than you want to use Bootstrap and Jekyll.

## Local Development

1. `bundle install`
2. `bundle exec jekyll serve`

## Styles

- You can override Bootstrap's [variable defaults](https://getbootstrap.com/docs/4.3/getting-started/theming/#variable-defaults) in `_sass/base/_custom.scss`.
- Bootstrap Sass files are located in `_sass/vendor/bootstrap/` and imported into `_sass/base/_custom.scss`, which is then imported into `_sass/main.scss` and finally compiled by `assets/css/main.scss`.

## Javascript

- Bootstrap's Javascript dependencies are located in `assets/javascript/vendor`.

## Layout

- All pages will use the `default` layout. This is configured in `_config.yml`. 