source "https://rubygems.org"
# Hello! This is where you manage which Jekyll version is used to run.
# When you want to use a different version, change it below, save the
# file and run `bundle install`. Run Jekyll with `bundle exec`, like so:
#
#     bundle exec jekyll serve
#
# This will help ensure the proper Jekyll version is running.
# Happy Jekylling!
gem "jekyll", "~> 4.3.3"
gem "minima", "~> 2.5" #if using Minima as a Gem-based theme
# gem "ghostly", path: './ghostly'  
gem 'html-proofer' #for link checking 

# This specifies a local path for ghostly, so you can edit it
# Installing as a gem via 'gem "ghostly"' would place the layout files 
# somewhere on your system where you are not easily able to change them

# If you want to use GitHub Pages, remove the "gem "jekyll"" above and
# uncomment the line below. To upgrade, run `bundle update github-pages`.
# gem "github-pages", group: :jekyll_plugins
# If you have any plugins, put them here!
group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.12" 
  gem "jekyll-seo-tag"
end
# Note that the 'gem "jekyll-seo-tag"' line is currently missing in Jekyll's 
# default installation, leading to an error. 

# Windows and JRuby does not include zoneinfo files, so bundle the tzinfo-data gem
# and associated library.
install_if -> { RUBY_PLATFORM =~ %r!mingw|mswin|java! } do
  gem "tzinfo", "~> 1.2"
  gem "tzinfo-data"
end

# Performance-booster for watching directories on Windows
gem "wdm", "~> 0.1.1", :install_if => Gem.win_platform?

group :jekyll_plugins do
  gem "bundler", "~> 2.0"
  gem "rake", "~> 12.0"
end
