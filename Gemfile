source 'https://rubygems.org'
ruby '2.2.1'

gem 'rails', '4.2.1'
gem 'sass-rails', '~> 5.0'
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.1.0'
gem 'jquery-rails'
gem 'turbolinks'
gem 'jquery-turbolinks'
gem 'jbuilder', '~> 2.0'
gem 'bootstrap-sass'
gem 'will_paginate-bootstrap'
gem 'devise', '~> 3.5.1'
gem 'paperclip', '~> 4.2'
gem 'aws-sdk', '< 2.0'
gem 'masonry-rails'
gem 'will_paginate', '~> 3.0.5'

group :development, :test do
  
  # THESE CAME WITH THE PROJECT
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug'
  # Access an IRB console on exception pages or by using <%= console %> in views
  gem 'web-console', '~> 2.0'
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'

  # this is where the tutorial starts 

	# Use sqlite3 as the database for Active Record
	gem 'sqlite3'
end

group :production do
	gem 'pg'
	gem 'rails_12factor'
end

group :doc do
	# bundle exec rake doc:rails generates the API under doc/api.
	gem 'sdoc', require: false
end