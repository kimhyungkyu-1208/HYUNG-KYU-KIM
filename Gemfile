source "https://rubygems.org"

# Local development build of the Minimal Mistakes remote-theme site.
# GitHub Pages builds remotely and ignores this Gemfile; it honors `remote_theme`
# and the whitelisted plugins declared in _config.yml.
gem "jekyll", "~> 3.9"

group :jekyll_plugins do
  gem "jekyll-remote-theme", "~> 0.4.3"
  gem "jekyll-include-cache"
  gem "jekyll-sitemap"
end

# Windows / JRuby timezone data
gem "tzinfo-data", platforms: [:mingw, :mswin, :x64_mingw, :jruby]

gem "webrick", "~> 1.7"
gem "kramdown-parser-gfm"

# Pin native-extension gems to versions that still support Ruby 2.6 (local builds).
gem "ffi", "~> 1.15.5"
gem "google-protobuf", "< 3.22"
