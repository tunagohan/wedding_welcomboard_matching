source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.5.1'

# *---* Core Gem *----------------------------------* #
gem 'rails', '~> 5.2.0'
gem 'mysql2', '>= 0.4.4', '< 0.6.0'
gem 'puma', '~> 3.11'
gem 'uglifier', '>= 1.3.0'
gem 'mini_racer', platforms: :ruby
gem 'bootsnap', '>= 1.1.0', require: false
gem 'coffee-rails', '~> 4.2'
gem 'turbolinks', '~> 5'
gem 'jbuilder', '~> 2.5'
# gem 'bcrypt', '~> 3.1.7'
# gem 'mini_magick', '~> 4.8'
# gem 'capistrano-rails', group: :development

# *---* Self Add Gem *------------------------------* #
gem 'jquery-rails', '~> 4.3', '>= 4.3.3'          # jQuery
gem 'font-awesome-rails', '~> 4.7', '>= 4.7.0.4'  # AwesomeFont
gem 'bootstrap', '~> 4.1.1'                       # Bootstrap4
gem 'sass-rails', '~> 5.0', '>= 5.0.7'            # Sass For Rails
gem 'material_icons', '~> 2.2', '>= 2.2.1'        # Material icon
# *-------------------------------------------------* #

group :development do
  gem 'web-console', '>= 3.3.0'
  gem 'listen', '>= 3.0.5', '< 3.2'
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
end

group :test do
  gem 'capybara', '>= 2.15', '< 4.0'
  gem 'selenium-webdriver'
  gem 'chromedriver-helper'
# *---* Self Add Gem *------------------------------* #
  gem 'database_cleaner', '~> 1.7'    # Erase the database for test execution
  gem 'faker', '~> 1.8', '>= 1.8.7'   # Test Dummy Data
end

group :development, :test do
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
# *---* Self Add Gem *------------------------------* #
  gem 'rspec', '~> 3.7'               # Testing Tool
  gem 'factory_bot', '~> 4.10'        # Test Data Support
  gem 'pry-rails'                     # Debug
  gem 'pry-byebug'                    # Debug
  gem 'pry-doc'                       # Debug
end

gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
