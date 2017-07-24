source 'https://rubygems.org'

gem 'rails', '4.2'
gem 'bootstrap-sass'
gem 'sprockets'
gem 'bcrypt-ruby'
gem 'faker'
gem 'will_paginate'
gem 'bootstrap-will_paginate'
gem 'puma'
gem 'sass-rails'
gem 'uglifier'
gem 'coffee-rails'
gem 'jquery-rails'
gem 'turbolinks'
gem 'jbuilder'

group :development, :test do
  gem 'sqlite3', platforms: :ruby
  gem 'rspec-rails', '2.13.1'
end

group :test do
  gem 'selenium-webdriver'
  gem 'capybara'
  gem 'factory_girl_rails'
  gem 'cucumber-rails', require: false
  gem 'database_cleaner', github: 'bmabey/database_cleaner'
end

group :production, :uat do
  # Database
  gem 'mysql2', '~> 0.3.18', platforms: :ruby
  gem 'activerecord-jdbcsqlite3-adapter', platforms: :jruby

  gem 'rails_12factor'
end
