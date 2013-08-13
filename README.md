## This fork
This is only relevant to people who need to set pushParameters and the pushAllTags command at the same time. This did not work in the version of the standalone tagmanager from max-favilli.

When this works, I'll ask Tobias (tmaier) to pull it.

I also added the latest version of max-favilli/tagmanager.


# tagmanager-rails

[![Gem Version](https://badge.fury.io/rb/tagmanager-rails.png)](http://badge.fury.io/rb/tagmanager-rails)
[![Dependency Status](https://gemnasium.com/tmaier/tagmanager-rails.png)](https://gemnasium.com/tmaier/tagmanager-rails)
[![Code Climate](https://codeclimate.com/github/tmaier/tagmanager-rails.png)](https://codeclimate.com/github/tmaier/tagmanager-rails)

This gem provides [Tag Manager][] for Rails asset pipeline.

It includes the CSS; SCSS and LESS version of the stylesheet.

## Version

Tag Manager version 2.4.2
[8d91c8683546409ab9ec459456f12afa1a0a870f](https://github.com/max-favilli/tagmanager/commit/8d91c8683546409ab9ec459456f12afa1a0a870f)

## Installation

Add the tagmanager-rails gem to your Gemfile.

```ruby
gem 'tagmanager-rails'
```

And run `bundle install`.

### Rails 3.1 or greater with asset pipeline *enabled*

The Tag Manager file will be added to the asset pipeline.

#### JS

Add the following line to `app/assets/javascripts/application.js`:

```js
//= require bootstrap-tagmanager
```

#### CSS, SCSS or LESS

Add the following line to `app/assets/stylesheets/application.css`:

```css
/*
 *= require bootstrap-tagmanager
 */
```

If you want to change the variables, include it with the Sass `@import` method

```scss
@import 'bootstrap-tagmanager';
```

Do the same if you are using LESS respectively.

## Contributing

Feel free to open an issue ticket if you find something that could be improved.

### Upgrading Tag Manager

1. Upgrade CSS and LESS version of stylesheet
1. Convert LESS to SCSS
1. Update `TAGMANAGER_VERSION`
1. Update Changelog and README

## Acknowledgements

Many thanks to [max-favilli](https://github.com/max-favilli) for [Tag Manager][] and all Rails committer for Rails.

Copyright [Tobias L. Maier](http://tobiasmaier.info), released under the MIT License.
Tag Manager itself is under Mozilla Public License. See [license.txt](https://github.com/max-favilli/tagmanager/blob/master/license.txt) of the project.

[Tag Manager]: https://github.com/max-favilli/tagmanager
