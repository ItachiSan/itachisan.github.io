source "https://rubygems.org"

# Dependencies for getting this site up and running
gem "jekyll"
gem "jekyll-paginate"
gem "jekyll-minifier"
gem "jemoji"

# Performance-booster for watching directories on Windows
gem "wdm", "~> 0.1.1", :platforms => [:mingw, :x64_mingw, :mswin]

# Fix time zone management issues
# https://jekyllrb.com/docs/installation/windows/#time-zone-management
platforms :mingw, :x64_mingw, :mswin, :jruby do
    gem "tzinfo", ">= 1", "< 3"
    gem "tzinfo-data"
end

# Development dependencies
group :development do
    gem "ruby-lsp"
end
