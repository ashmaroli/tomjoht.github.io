source 'https://rubygems.org'

if ENV['BUILD_MODE'] == 'released'
  gem 'jekyll', '~> 4.0'
else
  gem 'jekyll', github: 'jekyll/jekyll'
end

gem 'memory_profiler'
gem 'fileutils'
gem 'liquid', github: 'Shopify/liquid'

group :jekyll_plugins do
  gem 'jekyll-mentioji', github: 'ashmaroli/jekyll-mentioji', branch: 'reduce-allocations'
  gem 'jekyll-paginate'
  gem 'jekyll-redirect-from'
  gem 'jekyll-sitemap'
end
