source 'http://rubygems.org'

gem 'rails', '3.0.5'

group :production do
  gem 'pg', '0.10.1'
end
group :development do
  gem 'sqlite3-ruby', :require => 'sqlite3'
end

gem 'warden'
gem 'devise', "1.1.2"

gem 'haml'
gem 'rdiscount'
gem 'nokogiri'
gem 'icalendar'
gem 'cancan'

gem 'launchy'    # So you can do Then show me the page

group :test do
  gem "rspec", '2.0.0'
  gem "rspec-rails", '2.0.0'

  gem 'spork'
  gem 'capybara'

  gem 'database_cleaner'
  gem 'factory_girl', :git => "http://github.com/thoughtbot/factory_girl.git"
  gem 'fakeweb'
  gem 'timecop', :git => 'http://github.com/jtrupiano/timecop.git'
end
