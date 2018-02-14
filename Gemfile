# frozen_string_literal: true

source 'https://rubygems.org'

git_source(:github) { |repo_name| "https://github.com/#{repo_name}" }

gem 'administrate'
gem 'draper'
gem 'rails'

group :development, :test do
  gem 'cheat'
  gem 'factory_bot_rails'
  gem 'reek'
  gem 'rubocop'
end

group :development do
  gem 'annotate'
  gem 'brakeman'
  gem 'bullet'
  gem 'bundler-audit'
end

group :test do
  gem 'faker'
  gem 'json_spec'
  gem 'simplecov', require: false
end
