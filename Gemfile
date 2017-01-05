source 'https://rubygems.org'
ruby '2.3.1'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '4.2.7.1'
gem 'jquery-rails', '3.1.3'
gem 'foundation-rails', '~> 5.5'

group :development do
  # Use sqlite3 as the database for Active Record
  gem 'sqlite3', '1.3.10'
  gem 'binding_of_caller', '0.7.2'
  gem 'better_errors', '1.1.0'
  gem 'rubocop', '0.24.1'
end

group :test do
  gem 'capybara', '~> 2.3.0'
  gem 'capybara-screenshot', '~> 0.3.19'
  gem 'codeclimate-test-reporter', require: false
  gem 'database_cleaner', '~> 1.3.0'
  gem 'factory_girl_rails', '~> 4.4.1'
  gem 'faker', '~> 1.3.0'
  gem 'poltergeist', '~> 1.5.0'
  gem 'rack_session_access', '~> 0.1.1'
  gem 'rspec-rails', '~> 3.1'
  gem 'simplecov', '~> 0.10.0'
  gem 'webmock', '~> 1.18.0'
end

group :development, :test do
  #gem 'byebug'
end

group :production do
  gem 'passenger'
  gem 'pg'
  gem 'rails_12factor'
end

# Use SCSS for stylesheets
gem 'sass-rails', '~> 5.0.4'

# Use coffeescript
gem 'coffee-rails', '~> 4.1.0'

# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'

# See https://github.com/sstephenson/execjs#readme for more supported runtimes
gem 'therubyracer', platforms: :ruby

# Octokit GitHub API
gem 'octokit', '3.5.2'

# dotenv to load GitHub client variables
gem 'dotenv-rails', '0.9.0'

# RedCarpet to render markdown
gem 'redcarpet'

# SimpleCaptcha for, well, captchas
gem 'simple_captcha2', require: 'simple_captcha'

# Sidekiq handles jobs
gem 'sidekiq', '3.4.2'
gem 'sidekiq-status', '0.6.0'

# Validate emails
gem 'valid_email', require: 'valid_email/validate_email'

# Server monitoring
gem 'newrelic_rpm'

# Sinatra used for Sidekiq logging
gem 'sinatra', '~> 1.4.5'

# Automatically accept language if available
gem 'http_accept_language'
gem 'rails_12factor', group: :production