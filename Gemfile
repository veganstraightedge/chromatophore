source "https://rubygems.org"

ruby file: ".ruby-version"

# app server
gem "rails", "~> 8.0.0.rc2"
gem "bootsnap", require: false

# database
gem "sqlite3"

# webserver
gem "puma"
gem "thruster", require: false

# assets
gem "propshaft"
gem "importmap-rails"
gem "turbo-rails"
gem "stimulus-rails"
gem "bootstrap"

# JSON views
gem "jbuilder"

# pagination
gem "kaminari"

# authentication
gem "bcrypt"

# caching
gem "solid_cache"

# background jobs
gem "solid_queue"

# images
gem "image_processing" # variants
gem "down" # downloading
gem "http"

group :development, :test do
  gem "debug", platforms: %i[ mri windows ], require: "debug/prelude"
  gem "dotenv-rails"
  gem "overcommit"
  gem "squasher"
  gem "rspec-rails"
  gem "factory_bot_rails"

  # linters, formatters
  gem "erb_lint", require: false # views
  gem "brakeman", require: false # security
  gem "fasterer", require: false # performance

  # rubocop, codestyle guide and linting
  gem "rubocop", require: false
  gem "rubocop-capybara", require: false
  gem "rubocop-factory_bot", require: false
  gem "rubocop-performance", require: false
  gem "rubocop-rails", require: false
  gem "rubocop-rspec", require: false
  gem "rubocop-rspec_rails", require: false
end

group :test do
  gem "capybara"           # system testing
  gem "selenium-webdriver" # system testing
end

# windows dev
gem "tzinfo-data", platforms: %i[windows jruby]
