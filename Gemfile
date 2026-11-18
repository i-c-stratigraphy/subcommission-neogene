source "https://rubygems.org"

gem "jekyll", "~> 4.4"
gem "minima", "~> 2.5"
gem "webrick", "~> 1.9"

group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.18"
end

# Required explicitly for Ruby versions that no longer bundle these libraries.
gem "base64", "~> 0.3"
gem "bigdecimal", "~> 4.1"
gem "csv", "~> 3.3"
gem "logger", "~> 1.7"

platforms :windows, :jruby do
  gem "tzinfo", "~> 2.0"
  gem "tzinfo-data", "~> 1.2026"
end

gem "wdm", "~> 0.2", platforms: :windows
