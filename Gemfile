# frozen_string_literal: true

source 'https://rubygems.org'

group :test do
  gem 'coveralls', require: false
  gem 'rspec', '~> 3.8'
  gem 'awesome_print'
end

group :development do
  gem 'guard-rspec'
  gem 'ruby-prof'
end

group :test, :development do
  gem 'pry-byebug', platforms: :mri
end

# Specify your gem's dependencies in poparser.gemspec
gemspec
