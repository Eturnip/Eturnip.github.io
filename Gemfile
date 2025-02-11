# frozen_string_literal: true

source "https://rubygems.org"

gem "jekyll", "~> 4.2.0"
gem "jekyll-theme-chirpy", "~> 5.3", ">= 5.3.2"
gem "html-proofer", "~> 5.0", group: :test

group :jekyll_plugins do
  gem "jekyll-sitemap", "~> 1.4"
  gem "jekyll-feed"
end

platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

gem "wdm", "~> 0.2.0", :platforms => [:mingw, :x64_mingw, :mswin]

# Jekyll <= 4.2.0 compatibility with Ruby 3.0
gem "webrick", "~> 1.7"