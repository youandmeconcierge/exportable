source "https://rubygems.org"

# Declare your gem's dependencies in exportable.gemspec.
# Bundler will treat runtime dependencies like base dependencies, and
# development dependencies will be added by default to the :development group.
gemspec

# Declare any dependencies that are still in development here instead of in
# your gemspec. These might include edge Rails or gems from your path or
# Git. Remember to move these dependencies to your gemspec before releasing
# your gem to rubygems.org.

# To use debugger
# gem 'debugger'

gem 'mysql2'

group :test do
  gem 'database_cleaner'
  gem 'factory_girl_rails'
  gem 'capybara'
  gem 'shoulda-matchers'
  gem 'sqlite3'
end

group :test, :development do
  gem 'pry'
  gem 'rspec-rails'
end
