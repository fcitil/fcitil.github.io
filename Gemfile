source "https://rubygems.org"

# Core site
gem "jekyll", "~> 4.3.2"

# Ruby 3.4 compatibility: csv/logger/base64 moved out of default set
gem "csv", "~> 3.3"
gem "logger", "~> 1.6"
gem "base64"

# Theme and extras
gem "webrick", "~> 1.8"
gem "minima", "~> 2.5"

group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.12"
  gem "jekyll-seo-tag", "~> 2.8"
end

# Windows/JRuby timezone gems
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

# Windows watcher perf
gem "wdm", "~> 0.1.1", :platforms => [:mingw, :x64_mingw, :mswin] 