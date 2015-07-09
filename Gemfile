source 'https://rubygems.org'
ruby '2.2.1'

gem 'rails', '4.2.2'
gem 'sass-rails', '~> 5.0'
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.1.0'
gem 'jquery-rails'
gem 'turbolinks'
gem 'jbuilder', '~> 2.0'
gem 'sdoc', '~> 0.4.0', group: :doc
gem 'bootstrap-sass' 
gem 'devise', '~> 3.5.1'

group :development, :test do
gem 'sqlite3'   # this needs to be here and not on the top because when trying to upload to heroku it will give you problems
end

group :production do
	gem 'pg'
	gem 'rails_12factor'
end

group :development, :test do

  gem 'byebug'

  gem 'web-console', '~> 2.0'
  gem 'spring'
end

