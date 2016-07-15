source 'https://rubygems.org'

ruby '2.3.1'

gem 'rails', '~> 5.0.0'

# Server & Database
gem 'pg'
gem 'puma'

# Front-end
gem 'slim-rails'
gem 'sass-rails'
gem 'bootstrap-sass'
gem 'font-awesome-sass'
gem 'uglifier'
gem 'coffee-rails'
gem 'jquery-rails'
gem 'turbolinks'

# Back-end
gem 'devise'

group :development, :test do
  gem 'byebug', platform: :mri
  gem 'dotenv-rails'

  gem 'rspec', '~> 3.5'
  gem 'rspec-core', '~> 3.5'
  gem 'rspec-rails', '~> 3.5'
  gem 'shoulda', require: false
  gem 'factory_girl_rails'
end

group :development do
  gem 'web-console'
  gem 'listen'
  gem 'spring'
  gem 'spring-watcher-listen'

  # Guards
  gem 'guard-rspec', '~> 4.7', require: false
  gem 'guard-livereload'
  gem 'rack-livereload'
  gem 'terminal-notifier-guard', require: false
end
