source "https://rubygems.org"

# GitHub Pages gem includes Jekyll and other dependencies needed for GitHub Pages
gem "github-pages", group: :jekyll_plugins

# If you want to use a different theme, you can specify it here
gem "minima", "~> 2.5"

# If you have any additional plugins, put them here!
group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.12"
end

# Windows-specific gems
platforms :mingw, :x64_mingw, :mswin, :jruby do
  # tzinfo is needed for time zone information
  gem "tzinfo", ">= 1", "< 3"

  # tzinfo-data provides zoneinfo files for Windows and JRuby
  gem "tzinfo-data"

  # wdm is a performance-booster for watching directories on Windows
  gem "wdm", "~> 0.1.1", platforms: [:mingw, :x64_mingw, :mswin]
end

# Lock `http_parser.rb` gem to `v0.6.x` on JRuby builds
# Newer versions of the gem do not have a Java counterpart.
platforms :jruby do
  gem "http_parser.rb", "~> 0.6.0"
end
