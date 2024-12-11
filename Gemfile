source 'https://rubygems.org'

ruby file: '.ruby-version'

# app server
gem 'bootsnap', require: false
gem 'rails', '~> 8.0.0'

# database
gem 'sqlite3'

# webserver
gem 'puma'
gem 'thruster', require: false

# assets
gem 'importmap-rails'
gem 'propshaft'
gem 'stimulus-rails'
gem 'turbo-rails'

# UI framework getbootstrap.com
gem 'bootstrap'
gem 'bootstrap-icons-helper'
gem 'sassc-rails'

# JSON views
gem 'jbuilder'

# pagination
gem 'kaminari'

# authentication
gem 'bcrypt'

# caching
gem 'solid_cache'

# background jobs
gem 'solid_queue'

# images
gem 'down' # downloading
gem 'flickr' # Flickr API
gem 'http' # HTTP requests
gem 'image_processing' # variants

group :development, :test do
  gem 'debug', platforms: %i[mri windows], require: 'debug/prelude'
  gem 'dotenv-rails'
  gem 'factory_bot_rails'
  gem 'overcommit'
  gem 'rspec-rails'
  gem 'squasher'

  # linters, formatters
  gem 'brakeman', require: false # security
  gem 'erb_lint', require: false # views
  gem 'fasterer', require: false # performance

  # rubocop, codestyle guide and linting
  gem 'rubocop',             require: false
  gem 'rubocop-capybara',    require: false
  gem 'rubocop-factory_bot', require: false
  gem 'rubocop-performance', require: false
  gem 'rubocop-rails',       require: false
  gem 'rubocop-rspec',       require: false
  gem 'rubocop-rspec_rails', require: false
end

group :test do
  gem 'capybara'           # system testing
  gem 'selenium-webdriver' # system testing
end

# windows dev
gem 'tzinfo-data', platforms: %i[windows jruby]
