source 'https://rubygems.org'

gem 'rails', '3.2.6'

# Bundle edge Rails instead:
# gem 'rails', :git => 'git://github.com/rails/rails.git'

gem 'pg'

# Views
gem "slim"
gem "slim-rails"
gem "jquery-rails"

group :assets do
  gem 'sass-rails',   '~> 3.2.3'
  gem 'coffee-rails', '~> 3.2.1'
  gem 'uglifier', '>= 1.0.3'
  gem 'compass-rails'
  gem 'bootstrap-sass'
  gem "rails-backbone"
end

group :development, :test do
  gem "rspec-rails", "~> 2.9.0"
  gem "machinist"
  gem "database_cleaner"
  gem "shoulda-matchers"
  gem "jasmine"
end

group :production do
  gem "execjs"
end

group :development, :production do
  gem "thin"
end
