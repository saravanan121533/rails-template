source 'https://rubygems.org'

gem 'rails', '3.2.16'

# Bundle edge Rails instead:
# gem 'rails', :git => 'git://github.com/rails/rails.git'

gem 'pg'
gem 'foreigner' # I like foregin keys

gem 'haml-rails'

gem "cancan"

gem 'bootstrap-sass'


gem "quiet_assets" # We rarely need to see assets log in Rails log

gem "formtastic"   # A better way to build forms
gem "formtastic-bootstrap", git: "https://github.com/mjbellantoni/formtastic-bootstrap.git"

group :development do
  gem "thin"         # A better local server than Webrick
  gem "better_errors"       # Nicer error display
  gem "binding_of_caller"
end

gem 'rails_12factor', group: :production

group :development, :test do
  gem 'rspec-rails'
  gem 'capybara'
end

# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails',   '~> 3.2.3'
  gem 'coffee-rails', '~> 3.2.1'

  # See https://github.com/sstephenson/execjs#readme for more supported runtimes
  gem 'therubyracer', platforms: :ruby

  gem 'uglifier', '>= 1.0.3'
end

gem 'jquery-rails'

# To use ActiveModel has_secure_password
# gem 'bcrypt-ruby', '~> 3.0.0'

# To use Jbuilder templates for JSON
# gem 'jbuilder'

# Use unicorn as the app server
# gem 'unicorn'

# Deploy with Capistrano
# gem 'capistrano'

# To use debugger
# gem 'debugger'
