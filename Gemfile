source 'https://rubygems.org'

# official unofficial ruby-debug19 fix
# with the same gems as mentioned in 
# https://gist.github.com/1333785
source 'https://gems.gemfury.com/8n1rdTK8pezvcsyVmmgJ/' 

gem 'rails', '3.2.1'

# Bundle edge Rails instead:
# gem 'rails', :git => 'git://github.com/rails/rails.git'

gem 'pg'


# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails',   '~> 3.2.3'
  gem 'coffee-rails', '~> 3.2.1'

  # See https://github.com/sstephenson/execjs#readme for more supported runtimes
  gem 'therubyracer'

  gem 'uglifier', '>= 1.0.3'
end

gem 'jquery-rails'

# To use ActiveModel has_secure_password
# gem 'bcrypt-ruby', '~> 3.0.0'

# To use Jbuilder templates for JSON
# gem 'jbuilder'

# Use unicorn as the web server
# gem 'unicorn'

# Deploy with Capistrano
# gem 'capistrano'
group :development, :test do
  gem 'rspec-rails', '~> 2.8.1' #Note . Rspec will be installed as a dependency
  gem 'guard-rspec', '~> 0.6.0'
end

group :test do
  gem 'capybara', '~> 1.1.2'
  gem 'rb-inotify', '~> 0.8.8'
  gem 'libnotify', '~> 0.7.2'
  gem 'guard-spork', '~> 0.5.2'
  gem 'spork', '~> 1.0.0rc2'
end


group :development do
  gem 'linecache19',       '~> 0.5.13'
  gem 'ruby-debug-base19', '~> 0.11.26'
  gem 'ruby-debug19'
end
