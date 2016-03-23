source 'https://rubygems.org'


# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '4.2.5.1'
# Use ActiveModel has_secure_password
gem 'bcrypt', '~> 3.1.11', :require => 'bcrypt'
#Use Faker for make sample users with semi-realistic names & email address
gem 'faker', '~> 1.4.2'
#Use Carrierwave to handle an upload image in Micropost model
gem 'carrierwave', '~> 0.10.0'
#User MiniMagick for resizing image
gem 'mini_magick', '~> 3.8.0'
#Use Fog for image upload in production
gem 'fog', '~> 1.36.0'
#Use to paginate users in certain number
gem 'will_paginate',           '~> 3.0.7'
gem 'bootstrap-will_paginate', '~> 0.0.10'
# Use SCSS for stylesheets
gem 'sass-rails', '~> 5.0'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'
# Use CoffeeScript for .coffee assets and views
gem 'coffee-rails', '~> 4.1.0'
# See https://github.com/rails/execjs#readme for more supported runtimes
# gem 'therubyracer', platforms: :ruby
gem 'wdm', '~> 0.1.0'

# Use jquery as the JavaScript library
gem 'jquery-rails'
# Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
gem 'turbolinks'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.0'
# bundle exec rake doc:rails generates the API under doc/api.
gem 'sdoc', '~> 0.4.0', group: :doc

gem 'bootstrap-sass', '~> 3.2.0'
gem 'autoprefixer-rails'

# Use Unicorn as the app server
# gem 'unicorn'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'sqlite3', '~> 1.3.9'
  gem 'byebug', '~> 3.4.0'
  gem 'web-console', '~> 2.0.0.beta3'
  gem 'spring', '~> 1.1.3'
end

group :test do
  gem 'minitest-reporters', '1.0.5'
  gem 'mini_backtrace',     '0.1.3'
  gem 'guard-minitest',     '2.3.1'
end

group :production do
  gem 'pg',             '0.17.1'
  gem 'rails_12factor', '0.0.2'
  gem 'puma',           '2.11.1'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]