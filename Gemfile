# frozen_string_literal: true

source "https://rubygems.org"

gem "jekyll", "~> 4.3"  # Required for Chirpy
gem "jekyll-remote-theme"  # For loading Chirpy remotely
gem "webrick", "~> 1.8"    # For local serve on newer Ruby

gem "html-proofer", "~> 5.0", group: :test

platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

gem "wdm", "~> 0.2.0", :platforms => [:mingw, :x64_mingw, :mswin]
