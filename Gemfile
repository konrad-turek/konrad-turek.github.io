source "https://rubygems.org"
# Only used to preview the website on your own computer. GitHub ignores this file.
#
#   bundle install              (once, and after changes to this file)
#   bundle exec jekyll serve    (then open http://localhost:4000)

# Same Jekyll version and plugins as GitHub Pages
gem "github-pages", "~> 232", group: :jekyll_plugins

group :jekyll_plugins do
  gem "jekyll-include-cache"
  gem "jekyll-feed", "~> 0.12"
end

# Needed by Jekyll with newer Ruby versions
gem "webrick"
gem "csv"
gem "base64"
gem "bigdecimal"

# Windows does not include time zone files
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end
