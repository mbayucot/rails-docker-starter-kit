source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.7.3'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '~> 6.0.3', '>= 6.0.3.4'
# Use postgresql as the database for Active Record
gem 'pg', '>= 0.18', '< 2.0'
# Use Puma as the app server
gem 'puma', '~> 4.1'
# Use Redis adapter to run Action Cable in production
gem 'redis', '~> 4.0'
# Authorization solution
gem 'pundit', '~> 2.1.0'
# Generate JSON in a convention-driven manner
gem 'active_model_serializers', '0.10.10'
# Pagination
gem 'will_paginate', '3.3.0'
# Background processing
gem 'sidekiq', '~> 6.0.5'
# Scheduling extension for Sidekiq
gem 'sidekiq-scheduler', '~> 3.0.1'
# Client interface for the Sentry
gem "sentry-ruby"
gem "sentry-rails"

# Use Active Storage variant
# gem 'image_processing', '~> 1.2'

# Reduces boot times through caching; required in config/boot.rb
gem 'bootsnap', '>= 1.4.2', require: false

# Use Rack CORS for handling Cross-Origin Resource Sharing (CORS), making cross-origin AJAX possible
gem 'rack-cors'

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
  gem 'rspec-rails'
  gem 'rubocop', '~> 0.93.1', require: false
  gem 'faker'

  # Debugging
  gem 'debase'
  gem 'ruby-debug-ide'
end

group :development do
  gem 'listen', '~> 3.2'
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
end

group :test do
  gem 'database_cleaner'
  gem 'factory_bot_rails', '~> 5.1.1'
  gem 'pundit-matchers'
  gem 'rspec-json_expectations'
  gem 'rubocop-rspec', '~> 1.44.0', require: false
  gem 'shoulda-matchers', '~> 4.4.1'
  gem 'shoulda-callback-matchers', '~> 1.1.4'
  gem 'simplecov', require: false
  gem 'fuubar'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
