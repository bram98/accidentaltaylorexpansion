source "https://rubygems.org"
gemspec

gem "base64"
gem "csv"

gem "jekyll", "~> 3.9.0"
gem "jekyll-remote-theme" # This is the "engine" that pulls the theme
gem "just-the-docs"

gem "jekyll-github-metadata", ">= 2.15"

gem "jekyll-include-cache", group: :jekyll_plugins
gem "jekyll-sitemap", group: :jekyll_plugins

group :development, :test do
  gem "html-proofer", "~> 5.2"

  # Test Infrastructure
  gem 'rack'
  gem 'rackup'
  gem 'rspec'
  gem 'webrick'

  # Frontend a11y tests
  gem 'axe-core-capybara'
  gem 'axe-core-rspec'
  gem 'capybara'
  gem 'capybara-screenshot'
  gem 'selenium-webdriver'
end


