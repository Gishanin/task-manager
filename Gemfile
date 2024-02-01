source 'https://rubygems.org'
git_source(:github) { |repo| 'https://github.com/#{repo}.git' }

ruby '3.2.0'

gem 'rails', '~> 7.0.8'
gem 'pg', '~> 1.1'
gem 'puma', '~> 5.0'
gem 'tzinfo-data', platforms: %i[ mingw mswin x64_mingw jruby ]
gem 'bootsnap', require: false
gem 'rubocop'

group :development, :test do
  gem 'byebug'
  gem 'derailed_benchmarks'
  gem 'dotenv-rails'
  gem 'pry'
  gem 'rspec-rails', '~> 6.0', '>= 6.0.3'
  gem 'squasher'
  gem 'stackprof'
  gem 'devise'
end

group :test do
  gem 'factory_bot_rails'
  gem 'ffaker'
  gem 'fuubar'
  gem 'shoulda-matchers'
  gem 'simplecov', require: false
  gem 'vcr'
  gem 'webmock'
end

group :development do
  gem 'brakeman'
  gem 'bullet'
  gem 'letter_opener'
  gem 'web-console'
end
