source 'https://rubygems.org'

gem 'rails', '3.2.8'
gem 'jquery-rails'
gem 'haml'                              # Use HAML
gem 'capistrano'                        # Deploy with Capistrano
gem 'pg', '~> 0.12'                     # Use Posgresql Database
gem 'bcrypt-ruby', '~> 3.0'             # To use ActiveModel has_secure_password

group :development, :test do
  gem 'rspec-rails'
end

group :development do                   # The github documentation recommends this be in development, Railscasts say Test and Rails Tutorial says both
  gem 'haml-rails'                      # Use HAML generators etc.
  gem 'guard-rspec'
  gem 'guard-livereload'
  gem 'rack-livereload'
  gem 'yajl-ruby'                       # Optimize communication with the LiveReload Extension (increase JSON performance)
  gem 'guard-spork'
  gem 'annotate'                        # Run annotate on command line to add Schema Information to top of models. Must be rerun each time the data model changes to be up-to-date
end

group :test do
  gem 'factory_girl_rails'
  gem 'capybara'
  gem 'cucumber-rails'
  gem 'database_cleaner'
  gem 'rb-inotify'                      # Recomended for use with Guard in Rails Tutorial Listing 3.33. They enable system notifications from guard.
  gem 'libnotify'                       # Recomended for use with Guard in Rails Tutorial Listing 3.33. They enable system notifications from guard.
end

group :assets do                        # Gems used only for assets and not required in production environments by default.
  gem 'sass-rails',   '~> 3.2.3'
  gem 'coffee-rails', '~> 3.2.1'
  gem 'uglifier', '>= 1.0.3'
end



# Use unicorn as the app server
# gem 'unicorn'

# To use Jbuilder templates for JSON
# gem 'jbuilder'

# To use debugger
# gem 'debugger'

# Bundle edge Rails instead:
# gem 'rails', :git => 'git://github.com/rails/rails.git'
