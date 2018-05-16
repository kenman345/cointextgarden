source 'https://rubygems.org'

group :jekyll_plugins do
  gem 'github-pages'
  gem 'jekyll-feed'
  gem 'jekyll-minifier'
  gem 'jekyll-redirect-from'
  gem 'jekyll-seo-tag'
  gem 'jekyll-sitemap'
end

group :test do
  gem 'html-proofer'
  gem 'rake'
  gem 'rubocop'
end

# rubocop:disable SymbolArray
# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
# rubocop:enable SymbolArray

# Performance-booster for watching directories on Windows
gem 'wdm', '~> 0.1.0' if Gem.win_platform?
