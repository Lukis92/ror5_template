source 'https://rubygems.org'
ruby '2.3.1'

# Default gems
gem 'rails', '~> 5.0.0', '>= 5.0.0.1'
gem 'puma', '~> 3.0'
gem 'sass-rails', '~> 5.0'
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.2'
gem 'jquery-rails'
gem 'turbolinks', '~> 5'
gem 'jbuilder', '~> 2.5'

# Own gems
gem 'annotate' # annotate classes with schema and routes info
gem 'bootstrap-sass' # bootstrap Sass
gem 'devise' # authentication
gem 'font-awesome-rails' # web icons
gem 'heroku' # Heroku CLI
gem 'pg' # PostgreSQL database
gem 'slim-rails' # slim templating.
gem 'simple_form' # forms

group :development do
  gem 'better_errors' # better error page for Rack apps
  gem 'web-console'
  gem 'listen', '~> 3.0.5'
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
end

group :development, :test do
  gem 'byebug', platform: :mri
  gem 'factory_girl_rails' # support for multiple build strategies
  gem 'faker' # fake data generator
  gem 'rspec-rails', '~> 3.5' # testing framework
end

group :production do
  gem 'rails_12factor' # running rails app easier
end

group :test do
  gem 'capybara' # integration testing tool
  gem 'database_cleaner' # clean state for testing
  gem 'shoulda-matchers', '~> 3.1' # one-liners mini tests
end
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
