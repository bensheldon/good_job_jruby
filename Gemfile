source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

gem 'rails', '~> 6.1.3', '>= 6.1.3.1'
gem 'puma', '~> 5.0'

platforms :ruby do
  gem 'pg', '~> 1.1'
end

platforms :jruby do
  gem "activerecord-jdbcpostgresql-adapter"
  gem "warbler"
end

group :development, :test do
  gem 'pry'
  gem 'pry-byebug', platforms: [:mri, :mingw, :x64_mingw]
end
