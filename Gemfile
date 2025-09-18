# frozen_string_literal: true

source 'https://rubygems.org'

ruby '3.4.6'

gem 'sinatra'
gem 'rackup'
gem 'puma'   # For concurrent requests
gem 'httpparty'

group :test do
  gem 'rspec'
  gem 'rack-test'
  gem 'webmock'
end

group :development, :test do
  gem 'rubocop', require: false
end
