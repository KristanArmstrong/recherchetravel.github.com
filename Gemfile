# A sample Gemfile
source "https://rubygems.org"

# gem "rails"
require 'json'
require 'open-uri'
require 'jekyll'
versions = JSON.parse(open('https://pages.github.com/versions.json').read)

gem 'jekyll-sass-converter', '=1.2.0'
gem 'rouge', '<=1.6.2'

gem 'github-pages', versions['github-pages']
