SpreeSlugHistory
================

Avoids 404's when slugs change, thanks to `friendly_id` history module.

Installation
------------

Add spree_slug_history to your Gemfile:

```ruby
gem 'spree_slug_history', github: 'freego/spree_slug_history',
                          branch: '2-2-stable'
```

Bundle your dependencies and run the installation generator:

```shell
bundle
bundle exec rails g spree_slug_history:install
```

Testing
-------

First bundle your dependencies, then run `rake`. `rake` will default to building the dummy app if it does not exist, then it will run specs. The dummy app can be regenerated by using `rake test_app`.

```shell
bundle
bundle exec rake
```

Copyright (c) 2014 Alessandro Lepore, released under the New BSD License