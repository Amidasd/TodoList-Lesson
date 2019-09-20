source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

#ruby '2.5.5'

gem 'rails'
gem 'jquery-rails'
gem 'twitter-bootstrap-rails'
gem 'simple_form'
gem 'bootsnap', '>= 1.1.0', require: false
gem 'tzinfo-data', platforms: %i[mingw mswin x64_mingw jruby]

group :assets do
  gem 'sass-rails', '~> 5'
  gem 'uglifier'
  gem 'coffee-rails'
  gem 'therubyracer', platform: :ruby
end

group :production do
  gem 'pg'
end

group :development, :test do
  gem 'byebug'
end

group :development do
  gem 'web-console', '>= 3.3.0'
  gem 'sqlite3', '~> 1.4'
end


