source 'http://rubygems.org'

gem 'rails', '3.1.0'
gem 'sprockets', '2.0.0'

gem 'sqlite3'

gem 'backports', :platform => :rbx

# Asset template engines
group :assets do
  gem 'sass'
  gem 'sass-rails', '3.1.0'
  gem 'compass', :git => "git://github.com/chriseppstein/compass.git", :branch => "rails31"
  gem 'coffee-script'
  gem 'uglifier'
end

gem "haml-rails"
gem 'jquery-rails'

gem 'unicorn'
gem 'omniauth', :git => 'git://github.com/intridea/omniauth.git'
gem "sinatra", :require => "sinatra/base"
gem "mongo_mapper"
gem "mongomapper_ext"
gem "bson_ext"
gem "i18n"
gem "twitter"
gem "fb_graph"
gem "pony"
gem "bcrypt-ruby", :require => "bcrypt"
gem "rdiscount"
gem "ostatus", "~>0.0.9"
gem "osub", "~>0.0.6"
gem "opub"
gem "redfinger"
gem "nokogiri"
gem "whatlanguage"
gem "ruby-stemmer"
gem "tzinfo"
gem "rsa"
gem "exceptional"

# background job queue
gem "delayed_job", :git => "git://github.com/collectiveidea/delayed_job.git", :tag => "v2.1.4"
gem "delayed_job_mongo_mapper", :git => "git://github.com/earbits/delayed_job_mongo_mapper.git"
gem "whenever"

group :development, :test do
  gem 'rack-test'
  gem "database_cleaner"
  gem "factory_girl"
  gem "capybara"
  gem "rocco"
  gem "pygmentize"
  gem "mocha"
  gem "vcr"
  gem "simplecov", "~> 0.4.0", :require => false
  gem "launchy"
end

group :test do
  gem "webmock"
end
