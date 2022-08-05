source "https://rubygems.org"
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby "3.1.2"


gem "rails", "~> 7.0.3", ">= 7.0.3.1"


gem "puma", "~> 5.0"
gem 'sass-rails', '>= 6'
gem 'webpacker', '~> 5.4', '>= 5.4.3'
gem 'turbolinks', '~> 5.2', '>= 5.2.1'
gem "jbuilder"
gem "bootsnap", require: false
gem 'devise', '~> 4.8', '>= 4.8.1'


group :development, :test do
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
end

group :development do
  gem 'web-console', '>= 3.3.0'
  gem 'sqlite3', '~> 1.4'
end

group :production do
	gem 'pg', '~> 1.2', '>= 1.2.3'
	#gem 'rails_12factor', '0.0.2'
end


group :test do
  gem 'capybara', '>= 2.15'
  gem 'selenium-webdriver'
  gem 'webdrivers'
end

gem 'tzinfo-data'