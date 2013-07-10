source 'https://rubygems.org'

gem 'rails', '4.0.0'                  # Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'sqlite3'                         # Use sqlite3 as the database for Active Record
gem 'sass-rails', '~> 4.0.0'          # Use SCSS for stylesheets
gem 'uglifier', '>= 1.3.0'            # Use Uglifier as compressor for JavaScript assets
gem 'coffee-rails', '~> 4.0.0'        # Use CoffeeScript for .js.coffee assets and views
gem 'therubyracer', platforms: :ruby  # See https://github.com/sstephenson/execjs#readme for more supported runtimes
gem 'jquery-rails'                    # Use jquery as the JavaScript library
gem 'turbolinks'                      # Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
gem 'jbuilder', '~> 1.2'              # Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder

gem 'twitter-bootstrap-rails'         # Twitter Bootstrap for Rails
gem 'less-rails'                      # For twitter-bootstrap-rails
gem 'awesome_print'                   # For rails console

gem 'thin'                            # Web server. Usage: rails s thin
gem 'foreman'                         # Process manager. Usage: foreman start

group :development, :test do
  gem 'railroady'               # class diagram generator. Usage: rake diagram:all
  gem 'better_errors'           # better errors handler
  gem 'binding_of_caller'       # for better_errors
  gem 'meta_request'            # for RailsPanel (chrome extention)
  gem 'rack-mini-profiler'      # rails profiler
  gem 'brakeman'                # security scanner. Usage: brakeman [-o file.html]
  gem 'bullet'                  # query optimization # TODO need to configure
  gem 'annotate'                # annotate ActiveRecord models. Usage: annotate
end

group :test do
  gem "rspec-rails"             # test suite
  #gem 'guard-spork'             # Monitoring for changes in files
  #gem 'spork-rails'             # speed up test running. Support rails 4 only from github
  gem 'rr', require: false      # mocks/stubs
  gem 'factory_girl_rails'      # fixtures replacement
  gem 'database_cleaner'        # helper gem for rspec
  gem 'shoulda-matchers'        # rspec-compatible one-liners
  gem 'simplecov',      require: false # code coverage
  gem 'simplecov-html', require: false # generates HTML report
  gem 'capybara'                # user expirience testing
  gem 'selenium-webdriver'      # javascript driver for selenium
  gem 'launchy'                 # for capybara
end

group :test do # required for guard
  gem 'rb-inotify', require: false
  gem 'rb-fsevent', require: false
  gem 'rb-fchange', require: false
end
