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
gem "jbuilder"

# authentication
gem "bcrypt"

# caching
gem "solid_cache"

# background jobs
gem "solid_queue"

# image variants
gem "image_processing"

group :development, :test do
  gem "debug", platforms: %i[ mri windows ], require: "debug/prelude"

  # linter, security
  gem "brakeman", require: false

  # linter, rubocop
  gem "rubocop-rails-omakase", require: false
end

group :test do
  gem "capybara"           # system testing
  gem "selenium-webdriver" # system testing
end

# windows dev
gem "tzinfo-data", platforms: %i[ windows jruby ]
