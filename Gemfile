source "https://rubygems.org"
gem "jekyll", "~> 3.9.0" 
gem "minima", "~> 2.5"
gem "kramdown-parser-gfm"

group :jekyll_plugins do
 gem "jekyll-scholar"
 gem "jekyll-sitemap"
 gem "jekyll-feed"
 gem "jekyll-katex"
end

install_if -> { RUBY_PLATFORM =~ %r!mingw|mswin|java! } do
 gem "tzinfo", "~> 1.2"
 gem "tzinfo-data"
end

gem "wdm", "~> 0.1.1", :install_if => Gem.win_platform?
