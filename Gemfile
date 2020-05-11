source 'https://rubygems.org'

ruby '2.3.5'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '4.2.10'
# Use SCSS for stylesheets
gem 'sass-rails', '5.0.7'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '4.1.6'
# Use CoffeeScript for .coffee assets and views
gem 'coffee-rails', '4.2.2'

gem 'jquery-rails', '4.3.4'
# Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
gem 'turbolinks', '5.1.0'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '2.7.0'
# bundle exec rake doc:rails generates the API under doc/api.
gem 'sdoc', '1.0.0', group: :doc

group :development, :test do
  # Use sqlite3 as the database for Active Record
  gem 'sqlite3', '1.3.13'
  
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug', '10.0.0'

  # Access an IRB console on exception pages or by using <%= console %> in views
  gem 'web-console', '2.3.0'

  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring', '2.0.2'
end

gem "rubocop", "~> 0.54", group: :development, require: false

group :production do
  gem 'pg', '1.0.0'
  gem 'rails_12factor', '0.0.3'
end