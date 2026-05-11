source "https://rubygems.org"

# GitHub Pages dependency set. Pinned to a version that still supports
# Ruby 2.6 so local `bundle exec jekyll serve` works on the system Ruby.
# GitHub's build environment uses its own Ruby and will pick a compatible
# version from this gem family.
gem "github-pages", "~> 227", group: :jekyll_plugins

group :jekyll_plugins do
  gem "jekyll-feed"
  gem "jekyll-seo-tag"
  gem "jekyll-sitemap"
end

# Pin transitive deps that have dropped Ruby 2.6 support, so local
# `bundle install` resolves on the system Ruby. GitHub Pages' build
# environment uses a newer Ruby and resolves its own versions.
gem "ffi", "~> 1.15.5"
gem "google-protobuf", "~> 3.21.12"
gem "nokogiri", "~> 1.13.10"
gem "commonmarker", "~> 0.23.10"
gem "racc", "~> 1.6.0"
