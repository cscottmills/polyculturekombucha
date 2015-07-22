source 'https://rubygems.org'

group :development do
  require 'json'
  require 'open-uri'
  versions = JSON.parse(open('https://pages.github.com/versions.json').read)

  gem 'github-pages', versions['github-pages']
  gem 'sass'
end
