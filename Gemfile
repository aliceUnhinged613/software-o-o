# frozen_string_literal: true

source 'https://rubygems.org'

gem 'nokogiri', '>= 1.11.0'
gem 'rails', '~> 5.2', '>= 5.2.4.3'

# For appdata redirections (https -> http)
gem 'open_uri_redirections'
# Use SCSS for stylesheets
gem 'sassc-rails', '>= 2.1.2'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier'

gem 'fast_gettext', '>= 0.7.0'
gem 'gettext_i18n_rails', '>= 0.4.3'

# rails-i18n provides translations for ActiveRecord
# validation error messages
gem 'rails-i18n', '>= 5.1.3'

# Generate html based on markdown in views
gem 'redcarpet', '~> 3.4.0'

gem 'dalli'
gem 'hashie'
gem 'mini_magick'
gem 'minitest'
gem 'xmlhash', '>= 1.2.2'

gem 'prometheus_exporter'
gem 'puma_worker_killer'

# HTTP client library for OBS Client
gem 'faraday'
gem 'faraday_middleware'
gem 'multi_xml'

# needed to collect translatable strings
# not needed at production
group :development do
  gem 'byebug'
  # no need to load the gem via require
  # we only need the rake tasks
  gem 'gettext', '>= 1.9.3', require: false
  gem 'solargraph', '>= 0.39.8'
  gem 'web-console', '>= 3.7.0'
end

group :production do
  gem 'puma'
end

group :test do
  gem 'capybara', '>= 3.33.0'
  gem 'faker'
  gem 'geckodriver-helper'
  gem 'rubocop'
  gem 'rubocop-performance'
  gem 'selenium-webdriver'
  gem 'vcr'
  gem 'webmock'
end

# Debugging gems
# rbtrace does not install successfully in Docker and needs to be manually enabled
# gem 'rbtrace', require: false
