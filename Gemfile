source 'https://rubygems.org'
ruby '2.0.0'
# Application gems
gem 'rails', '4.0.3'
gem 'jquery-rails'
gem 'devise'
gem 'simple_form', '~> 3.0.1'
gem "paperclip", "4.1.1"
gem "paperclip-dropbox"
gem 'aws-sdk', '~> 1.36.1'
gem "masonry-rails"
gem 'faker'
gem 'will_paginate', '~> 3.0.5'
gem 'bootstrap-will_paginate'
gem 'acts_as_follower'
gem 'pg'

group :development, :test do
	gem 'rspec-rails', '2.14.1'
  # The following optional lines are part of the advanced setup.
  gem 'factory_girl_rails', '~> 4.4.1'
  gem 'guard-rspec', '4.2.8'
  gem 'spork-rails'
  gem 'guard-spork'
  gem 'childprocess'
  gem 'terminal-notifier-guard'
  gem "better_errors"
  gem 'annotate', ">=2.6.0"
end

group :test do
  gem 'selenium-webdriver', '~> 2.40.0'
  gem 'capybara', '2.2.1'
  # gem 'capybara-webkit'
  gem 'cucumber-rails', '~> 1.4.0', :require => false
  gem 'database_cleaner', github: 'bmabey/database_cleaner'

  # Uncomment this line on OS X.
  #gem 'growl', '1.0.3'

  # Uncomment these lines on Linux.
  # gem 'libnotify', '0.8.0'

  # Uncomment these lines on Windows.
  # gem 'rb-notifu', '0.0.4'
  # gem 'win32console', '1.3.2'
end
group :production do
	gem 'rails_12factor'
end


# Use SCSS for stylesheets
gem 'sass-rails'	
# Use CoffeeScript for .js.coffee assets and views
gem 'coffee-rails'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier'
# Add Bootstrap
gem 'bootstrap-sass'
gem 'bcrypt-ruby', '~> 3.1.5'

# Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
gem 'turbolinks'
gem 'jquery-turbolinks'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder'

group :doc do
  # bundle exec rake doc:rails generates the API under doc/api.
  gem 'sdoc', require: false
end

gem 'protected_attributes'

# Use ActiveModel has_secure_password
# gem 'bcrypt-ruby', '~> 3.0.0'

# Use unicorn as the app server
# gem 'unicorn'

# Use Capistrano for deployment
# gem 'capistrano', group: :development

# Use debugger
# gem 'debugger', group: [:development, :test]


# See https://github.com/sstephenson/execjs#readme for more supported runtimes
# gem 'therubyracer', platforms: :ruby
