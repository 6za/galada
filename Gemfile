source "https://rubygems.org"

gem "bundler"
#gem "jekyll", ">= 3.8.4"
gem "jekyll", github: "jekyll/jekyll"
gem "liquid-c"

# https://forestry.io/blog/how-i-reduced-my-jekyll-build-time-by-61/
group :jekyll_plugins do
  gem "jekyll-archives"
  gem "jekyll-commonmark"
  gem "jekyll-feed"
  gem "jekyll-include-cache"
  gem "jekyll-remote-theme"
  gem "jekyll-seo-tag"
  gem "jekyll-sitemap"
end

gem "jekyll-paginate"
#gem "jekyll-sitemap"
gem 'jekyll-spaceship'

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem "tzinfo-data", platforms: [:mingw, :mswin, :x64_mingw, :jruby]

# Performance-booster for watching directories on Windows
gem "wdm", "~> 0.1.0" if Gem.win_platform?

