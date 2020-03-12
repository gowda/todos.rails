source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.6.3'

rails_version = '6.0.2'
gem 'actionpack', "~> #{rails_version}"
gem 'actionview', "~> #{rails_version}"
gem 'activemodel', "~> #{rails_version}"
gem 'activerecord', "~> #{rails_version}"
gem 'activesupport', "~> #{rails_version}"
gem 'railties', "~> #{rails_version}"
gem 'sprockets-rails', '>= 2.0.0'

gem 'pg', '>= 0.18', '< 2.0'
gem 'puma', '~> 4.1'
gem 'sass-rails', '>= 6'
gem 'jbuilder', '~> 2.7'

group :development, :test do
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
end

group :development do
  gem 'web-console', '>= 3.3.0'
  gem 'listen', '>= 3.0.5', '< 3.2'
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
end

