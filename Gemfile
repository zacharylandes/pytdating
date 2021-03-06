source 'https://rubygems.org'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end

ruby '2.4.1'

gem 'rails', '~> 5.1.5'
gem "omniauth-google-oauth2", "~> 0.2.1"
gem 'aws-sdk-rails'
gem 'sass-rails', '~> 5.0'
gem 'pg', '>= 0.18', '< 2.0'
gem 'puma', '~> 3.7'
gem 'zip-codes'
gem 'sprockets'
gem 'bootstrap-slider-rails'
gem 'figaro'
gem 'faraday'
gem 'carrierwave-aws'
gem 'carrierwave', '~> 1.0'
gem 'mini_magick'
gem 'mailboxer'
gem 'will_paginate', '~> 3.1.0'
gem "active_model_serializers"
gem 'redis'
gem 'faker'
gem 'sidekiq'
gem 'mailgun-ruby'
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.2'
gem 'turbolinks', '~> 5'
gem 'jbuilder', '~> 2.5'
gem 'rack-cors'



group :development, :test do
  gem 'rspec-rails'
  gem 'pry'
  gem 'factory_bot_rails'
  gem 'capybara'
  gem 'launchy'
  gem "letter_opener"
  gem 'database_cleaner'
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
  # Adds support for Capybara system testing and selenium driver
  # gem 'capybara', '~> 2.13'
  gem 'selenium-webdriver'
end

group :development do
  gem 'web-console', '>= 3.3.0'
  gem 'listen', '>= 3.0.5', '< 3.2'
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
