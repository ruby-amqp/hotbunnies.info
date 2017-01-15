# March Hare Documentation

This is a documentation site for [March Hare](http://rubymarchhare.info), a dead easy
to use RabbitMQ client for JRuby.


## Install Dependencies

To run the site generator yourself, you'll need to first have Ruby installed.
Python is also required, as syntax-highlighting of code blocks is handled by pygments.

If installing Ruby from source, a prerequisite is the libyaml dev package.

To install dependencies with Bundler:

    bundle install --binstubs


## How to run a development server

    ./bin/jekyll serve --watch

then navigate to [localhost:4000](http://localhost:4000)

## How to regenerate the site

    ./bin/jekyll build


## License & Copyright

Copyright (C) 2013-2017 Michael S. Klishin.

Distributed under the MIT License.
