source 'https://rubygems.org'


# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '4.2.4'
# Use sqlite3 as the database for Active Record
group :development, :test do
  gem 'sqlite3'
  gem 'rspec-rails'
end

group :test do
  gem 'selenium-webdriver'
#  gem 'capybara', '2.1.0'
  gem 'capybara'
end

# Use SCSS for stylesheets
gem 'sass-rails'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier'
# Use CoffeeScript for .coffee assets and views
gem 'coffee-rails'

# 以下がないと，しかもバージョンが1.8じゃないとサーバーでhomeやHelpにアクセスした時にエラーがでる
gem 'coffee-script-source', '1.8.0'

# See https://github.com/rails/execjs#readme for more supported runtimes
# gem 'therubyracer', platforms: :ruby

# Use jquery as the JavaScript library
gem 'jquery-rails'
# Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
gem 'turbolinks'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder'
# bundle exec rake doc:rails generates the API under doc/api.
group :doc do
  gem 'sdoc', require: false
end

# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use Unicorn as the app server
# gem 'unicorn'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

#group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
#  gem 'byebug'
#end

#group :development do
  # Access an IRB console on exception pages or by using <%= console %> in views
#  gem 'web-console', '~> 2.0'
#end

group :production do
  gem 'pg'
  gem 'rails_12factor'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
