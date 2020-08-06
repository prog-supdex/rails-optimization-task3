source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.6.3'

gem 'rails', '~> 5.2.3'
gem 'pg', '>= 0.18', '< 2.0'
gem 'puma', '~> 3.11'
gem 'bootsnap', '>= 1.1.0', require: false
gem 'pghero', '~> 2.6'
gem 'pg_query', '>= 0.9.0'
gem 'activerecord-import', '~> 1.0', '>= 1.0.6'
gem 'yajl-ruby', '~> 1.4', '>= 1.4.1', require: 'yajl'

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
end

group :development do
  # Access an interactive console on exception pages or by calling 'console' anywhere in the code.
  gem 'web-console', '>= 3.3.0'
  gem 'listen', '>= 3.0.5', '< 3.2'
  gem 'ruby-prof', '~> 1.4', '>= 1.4.1'
  gem 'bullet', '~> 6.1'
  gem 'rack-mini-profiler', '~> 2.0', '>= 2.0.4'
end

group :test do
  gem 'rspec-benchmark', '~> 0.6.0'
  gem 'rspec-rails', '~> 4.0', '>= 4.0.1'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
