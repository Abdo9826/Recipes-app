source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '3.1.2'
gem 'rubocop', '>= 1.0', '< 2.0'

gem 'devise'
gem 'rails', '~> 7.0.4'
gem 'sprockets-rails'

gem 'childprocess'
gem 'ffi'
gem 'cancancan'

gem 'importmap-rails'
gem 'pg', '~> 1.1'
gem 'puma', '~> 5.0'

gem 'stimulus-rails'
gem 'turbo-rails'

gem 'bootsnap', require: false
gem 'jbuilder'
gem 'tzinfo-data'

group :development, :test do
  gem 'debug', platforms: %i[mri mingw x64_mingw]
end

group :development do
  gem 'letter_opener'
  gem 'web-console'
end

group :test do
  gem 'capybara'
  gem 'selenium-webdriver'
  gem 'webdrivers'
end
