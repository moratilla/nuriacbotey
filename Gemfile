source "https://rubygems.org"

gem "nokogiri", ">= 1.11.0.rc4"
gem "jekyll", "~> 4.3.4"

# Theme for this site
gem "jekyll-theme-hydejack", "~> 9.2.1"

# Test links and HTML validity
gem "html-proofer"

# If you have any plugins, put them here!
group :jekyll_plugins do
  gem "jekyll-feed"
  gem "jekyll-default-layout"
  gem "jekyll-paginate"
  gem "jekyll-twitter-plugin"
  gem "jekyll-youtube"
  gem "jekyll-sitemap"
  gem "jekyll-seo-tag"
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
# and associated library.
install_if -> { RUBY_PLATFORM =~ %r!mingw|mswin|java! } do
  gem "tzinfo", "~> 2.0.4"
  gem "tzinfo-data"
end

# Performance-booster for watching directories on Windows
gem "wdm", "~> 0.1.0", :install_if => Gem.win_platform?
gem "classifier-reborn"
