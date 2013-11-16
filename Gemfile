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
  gem 'railroady'               # Class diagram generator. Usage: rake diagram:all
  gem 'better_errors'           # Better errors handler
  gem 'binding_of_caller'       # For better_errors
  gem 'meta_request'            # For RailsPanel (chrome extention)
  gem 'rack-mini-profiler'      # Rails profiler
  gem 'brakeman'                # Security scanner. Usage: brakeman [-o file.html]
  gem 'bullet'                  # Query optimization # TODO need to configure
  gem 'annotate'                # Annotate ActiveRecord models. Usage: annotate
  gem 'zeus'                    # Boot any rails app in under a second.
end

group :test do
  gem "rspec-rails"             # Test suite
  gem 'factory_girl_rails'      # Fixtures replacement
  gem 'database_cleaner'        # Helper gem for rspec
  gem 'shoulda-matchers'        # Rspec-compatible one-liners
  gem 'simplecov', require: false # Code coverage
  gem 'capybara'                # User expirience testing
  gem 'selenium-webdriver'      # Javascript driver for selenium
  gem 'launchy'                 # For capybara
end

