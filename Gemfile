source "https://rubygems.org"

gem "github-pages", group: :jekyll_plugins
gem "minimal-mistakes-jekyll", "~> 4.26"
gem 'webrick'

group :jekyll_plugins do
  gem 'jekyll-include-cache'
  gem "jekyll-feed", "~> 0.12"
end

platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

gem "wdm", "~> 0.1.1", platforms: [:mingw, :x64_mingw, :mswin]
gem "http_parser.rb", "~> 0.6.0", platforms: [:jruby]

