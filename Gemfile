# frozen_string_literal: true
source "https://rubygems.org"
ruby "3.2.3"

# Windows and JRuby does not include zoneinfo files, so bundle the tzinfo-data gem
# and associated library.
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

# gem "rails"
gem "jekyll"
gem 'wdm', '>= 0.1.0' if Gem.win_platform?
gem "webrick"
gem "beautiful-jekyll-theme", "6.0.1"

group :jekyll_plugins do
  gem "jekyll-sitemap"
  gem "jekyll-feed"
  gem "jekyll-seo-tag", ">= 1.5"
  gem "jekyll-redirect-from"
  gem "jekyll-paginate-v2"
end
