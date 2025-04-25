source "https://rubygems.org"

gem "github-pages", group: :jekyll_plugins

# gem "tzinfo-data"
# gem "wdm", "~> 0.1.0" if Gem.win_platform?
gem 'faraday-retry'

# Windows and JRuby does not include zoneinfo files, so bundle the tzinfo-data gem
# and associated library.
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem 'tzinfo', '~> 2.0'
  gem "tzinfo-data"
end


# If you have any plugins, put them here!
group :jekyll_plugins do
  gem "jekyll-paginate-v2"
  gem "jekyll-sitemap"
  gem "jekyll-gist"
  gem "jekyll-feed"
  gem "jemoji"
  gem "jekyll-include-cache"
  gem "jekyll-algolia"
  gem "jekyll-seo-tag"
end

# Performance-booster for watching directories on Windows
# Windows Directory Monitor (WDM) is only needed on Windows systems
if Gem.win_platform?
  gem "wdm", "~> 0.2.0", :platforms => [:mingw, :x64_mingw, :mswin]
end

# Lock `http_parser.rb` gem to `v0.6.x` on JRuby builds since newer versions of the gem
# do not have a Java counterpart.
gem "http_parser.rb", "~> 0.6.0", :platforms => [:jruby]

gem "webrick", "~> 1.8"
