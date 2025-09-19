# frozen_string_literal: true

source 'https://rubygems.org'

ruby '3.4.6'

gem 'httpparty'
gem 'puma' # For concurrent requests
gem 'rackup'
gem 'sinatra'

group :test do
  gem 'rack-test'
  gem 'rspec'
  gem 'webmock'
end

group :development, :test do
  gem 'rubocop', require: false
  gem 'rubocop-rspec', require: false
end
