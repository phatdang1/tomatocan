source 'http://rubygems.org'
ruby "1.9.2"

gem 'mandrill'
gem 'devise', '~> 2.2.4'
gem 'fog'   #, '1.6.0'
gem 'unf' 
gem 'carrierwave'
gem 'stripe'
#gem "debugger-pry", :require => "debugger/pry"
gem 'aws-s3'
gem 'aws-sdk'

gem 'rails', '3.1.0'
gem 'bcrypt-ruby', '3.0.1'

gem 'event-calendar', :require => 'event_calendar'
#gem "paperclip", "~> 2.0"
#gem 'rmagick'

# Bundle edge Rails instead:
# gem 'rails',     :git => 'git://github.com/rails/rails.git'

group :development, :test do
  gem 'sqlite3-ruby', :require => 'sqlite3'
end

group :production do
   gem 'pg' 
# rake db:create:all
# rails s -e production
#  gem 'sqlite3-ruby', :require => 'sqlite3'
end

# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails', "  ~> 3.1.0"
  gem 'coffee-rails', "~> 3.1.0"
  gem 'uglifier'
end

gem 'jquery-rails'

# Use unicorn as the web server
# gem 'unicorn'

# Deploy with Capistrano
# gem 'capistrano'

# To use debugger
# gem 'ruby-debug19', :require => 'ruby-debug'

group :test do
  # Pretty printed test output
  gem 'turn', :require => false
end
