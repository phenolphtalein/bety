source "http://rubygems.org"

gem "rails", "3.0.18"
gem "query_reviewer", "0.1.6"
gem "nokogiri"
gem "narray", "0.6.0.4"
gem "choice", "0.1.6"
gem "comma", "3.0.4"
gem "json", "1.8.2"
gem "multi_json", "1.3.6"
gem "railroad", "0.5.0"
gem "recaptcha", "0.3.4", :require => "recaptcha/rails"
gem "ruby-graphviz", "1.0.8"
gem "safe_attributes"
gem "seer", "0.10.0"
gem "tzinfo", "0.3.35"
gem "will_paginate", "3.0.4"
gem "bootstrap-will_paginate"
gem "spatial_adapter"

# MySQL, comment out PostgreSQL section
#gem "mysql2"
#gem "ruby-mysql" # for data upload scripts in local
#gem "activerecord-mysql2-adapter"

# Postgresql, comment out MySQL section
gem "pg"
gem "activerecord-postgis-adapter"

group :development, :test do
  # Although rspec-rails is mainly for the test environment, we
  # include it in development in case we want to have access to
  # RSpec-specific generators.
  gem "rspec-rails"
  gem "sqlite3", "1.3.3"
end



group :test do
  # phasing out webrat:    
  # gem "webrat", "0.7.1"
  gem "capybara"
  gem "database_cleaner"
end

# If you have difficulty installing or don't wish to install capybara-webkit,
# run bundle install with the "--without javascript_testing" option:
#
#     bundle install --without javascript_testing
#
group :javascript_testing do
  gem "capybara-webkit"
end

# This group is used by RSpec if the environment variable RAILS_DEBUG is set to
# "true":
group :debug do
  gem "selenium-webdriver"
  gem "pry"
end

# Comment this out if you can't or don't wish to install capybara-webkit:

group :production do
#  gem "rmagick", "2.13.1"
  gem "passenger"
end

