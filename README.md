# Sinatra Skeleton

Sinatra skeleton is a source code to make a sinatra project more organized. It
was provided by DevBootcamp and I decided to clone it and make some improvements.

## Getting Started

The Skeleton is build with the following gems:

* [ActiveRecord](https://github.com/rails/rails/tree/master/activerecord) - Active
Record connects classes to relational database tables to establish an almost 
zero configuration persistence layer for applications.
* [ActiveSuport](https://github.com/rails/rails/tree/master/activesupport) - Active 
  Support is a collection of utility classes and standard library extensions
* [Postgres]() - Database adapter
* [Rake](https://github.com/ruby/rake) - Rake is a Make-like program implemented in Ruby
* [RSpec](https://github.com/rspec/rspec) - Behaviour Driven Development
* [Sinatra](https://github.com/sinatra/sinatra) - Web Framework
* [Shotgun](https://github.com/rtomayko/shotgun) - Automatic rackup reload
* [Thin](https://github.com/macournoyer/thin) - Web Server
* [Sprockets](https://github.com/rails/sprockets) - Assets Pipe line
* [Uglifier](https://github.com/lautis/uglifier) - Js compressor
* [Sass](https://github.com/sass/sass) - Scss compressor

### Folder structure:
```
    app/
      assets/
        images/
        javascripts/
          application.js
        stylesheets/
          application.scss

      controllers/
        index.rb

      helpers/
        README       # Related helper methods

      models/
        README       # Related model methods

      views/
        index.erb    # Specific view
        layout.erb   # Common layout

    config/
      database.rb    # Database configuration
      environment.rb # Environment configuration

    db/
      migrate/       # Migration folder
      seeds.rb       # Seeds file

    source/
      .gitignore
      .rspec

    spec/
      spec_helper.rb

    config.ru # Rack use configuration file with extension .ru, that
              # instructs Rack::Builder what middleware should it
              # use and in which order.
    Gemfile
    Gemfile.lock
    Rakefile
    README.md
```

## Installing

Clone the repository on your local machine and run bundle.

```shell
git clone git@github.com:rafaelrochasilva/sinatra-skeleton.git
```
```shell
bundle install
```

## Running the server
The shotgun/thin web app server runs on http://127.0.0.1:9393/ port.
To run the app, just type the command:


```shell
shoutgun
```

## License

(The MIT License)

Copyright (c) 2014-2017 Rafael Rocha <rafaelrochasilva@gmail.com>

Permission is hereby granted, free of charge, to any person obtaining
a copy of this software and associated documentation files (the
'Software'), to deal in the Software without restriction, including
without limitation the rights to use, copy, modify, merge, publish,
distribute, sublicense, and/or sell copies of the Software, and to
permit persons to whom the Software is furnished to do so, subject to
the following conditions:

The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED 'AS IS', WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY
CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT,
TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE
SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
