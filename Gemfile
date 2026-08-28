source "https://rubygems.org"

# Local dev + CI both build with plain Jekyll 4 (not the `github-pages` gem,
# which pins Jekyll 3.8 and no longer runs on Ruby 3).
# Serve with: bundle exec jekyll serve --livereload
gem "jekyll", "~> 4.3"

group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.17"
  gem "jekyll-seo-tag", "~> 2.8"
end

# Default gems removed from Ruby 3.x that Jekyll's deps still expect.
gem "webrick", "~> 1.8"
gem "csv"
gem "base64"
gem "bigdecimal"
