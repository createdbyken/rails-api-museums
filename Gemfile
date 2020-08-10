source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.5.3'

gem 'rails', '~> 5.2.1'       # Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'pg'                      #using postgresql for main database
gem 'puma', '~> 3.11'         # Use Puma as the app server
gem 'bootsnap', '>= 1.1.0', require: false  # Reduces boot times through caching; required in config/boot.rb
gem 'rack-cors'               # Use Rack CORS for handling Cross-Origin Resource Sharing (CORS)
gem 'jbuilder', '~> 2.5'      # Build JSON APIs with ease. 
gem 'nokogiri'

# gem 'mini_magick', '~> 4.8' # Use ActiveStorage variant


group :development, :test do
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw] # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'pry'
end

group :development do
  gem 'listen', '>= 3.0.5', '< 3.2'
  gem 'spring'      # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring-watcher-listen', '~> 2.0.0'
  gem 'sqlite3'     # Use sqlite3 as the database for Active Record
end

gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby] # Windows does not include zoneinfo files, so bundle the tzinfo-data gem
