source 'https://rubygems.org'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '4.0.0.rc2'

gem 'bcrypt-ruby', '~>3.0.0'
gem 'bootstrap-sass'

# Use sqlite3 as the database for Active Record
group :development, :test do
	gem 'sqlite3'
	gem 'rspec-rails'
	gem 'guard-rspec'
	gem 'annotate' 

end

# Gems used only for assets and not required
# in production environments by default
group :assets do
	# Use SCSS for stylesheets
	gem 'sass-rails', '~> 4.0.0.rc2'

	# Use Uglifier as compressor for JavaScript assets
	gem 'uglifier', '>= 1.3.0'

	# Use CoffeeScript for .js.coffee assets and views
	gem 'coffee-rails', '~> 4.0.0'
end

# See https://github.com/sstephenson/execjs#readme for more supported runtimes
# gem 'therubyracer', platforms: :ruby

# Use jquery as the JavaScript library
gem 'jquery-rails'

# added by book suggestion
group :test do
	gem 'rspec-rails'
	gem 'capybara'
	gem 'rb-fsevent', :require => false
	gem 'growl'
	gem 'guard-spork'
	gem 'spork'
end

# added by book suggestion
# this is for PostgreSQL instead of sqlite3
group :production do
	gem 'pg'
end

# added by Cyndi for the attributes
gem 'protected_attributes'

# Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
gem 'turbolinks'

# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 1.2'

group :doc do
  # bundle exec rake doc:rails generates the API under doc/api.
  gem 'sdoc', require: false
end

# Use ActiveModel has_secure_password
# gem 'bcrypt-ruby', '~> 3.0.0'

# Use unicorn as the app server
# gem 'unicorn'

# Use Capistrano for deployment
# gem 'capistrano', group: :development

# Use debugger
# gem 'debugger', group: [:development, :test]
