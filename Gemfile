# frozen_string_literal: true
source "https://rubygems.org"
ruby "3.2.3"

gem "jekyll", "~> 4.3.3"
#gem "minima", "~> 2.5" # default theme
gem "beautiful-jekyll-theme", "6.0.1"

# put plugins here
group :jekyll_plugins do
  gem "jekyll-sitemap"
  gem "jekyll-feed", "~> 0.12"
  gem "jekyll-seo-tag", ">= 1.5"
  gem "jekyll-redirect-from"
  gem "jekyll-paginate-v2"
  gem "webrick"
end

# Windows and JRuby does not include zoneinfo files, so bundle the tzinfo-data gem
# and associated library.
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

# Performance-booster for watching directories on Windows
gem "wdm", "~> 0.1.1", :platforms => [:mingw, :x64_mingw, :mswin]

# Lock `http_parser.rb` gem to `v0.6.x` on JRuby builds since newer versions of the gem
# do not have a Java counterpart.
gem "http_parser.rb", "~> 0.6.0", :platforms => [:jruby]
