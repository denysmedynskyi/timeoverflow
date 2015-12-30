source 'https://rubygems.org'
ruby '2.2.2'

gem 'rails', '~> 4.2'
gem 'rails-i18n'
gem 'rails_12factor'
gem "rdiscount"
gem 'high_voltage', '~> 2.1.0'
gem 'activeadmin', github: 'activeadmin'
gem 'has_scope'
gem 'responders', '~> 2.0'
gem 'pundit'
gem 'pg', '0.17.1'
gem 'hstore_translate'
gem 'dalli'
gem 'slim-rails' # much better than haml
gem "devise"
gem "http_accept_language"
gem 'thin'
gem 'foreman'
gem 'dotenv-rails'
gem 'kaminari'
gem "haml-rails"
gem "simple_form", ">= 3.0.0"
gem "awesome_print"
gem "rest-client"
gem 'memcachier'
gem 'rollbar'
gem 'travis-lint'
gem "shelly-dependencies"
gem 'whenever', :require => false
gem 'prawn'
gem 'prawn-table'
gem 'bundler', '>= 1.10.6'
gem 'elasticsearch-model'
gem 'elasticsearch-rails'

# Assets
gem 'jquery-rails'
gem 'jquery-ui-rails'
gem 'bootstrap-sass'
gem 'sass-rails', '~> 5.0.1'
gem 'coffee-rails'
gem 'ngannotate-rails'
gem 'uglifier', '>= 1.0.3'
gem 'select2-rails'

group :development do
  gem "binding_of_caller"
  gem "better_errors"
  gem "rubocop"
  gem "haml-lint"
  gem 'web-console', '~> 2.0'
  gem "rails-erd"
end

group :development, :test do
  gem "rspec-rails", '~> 2.14'
  gem "capybara", '~> 2.4.4'
  gem "byebug"
end

group :test do
  # Needed for TravisCI
  gem 'rake'
  gem "database_cleaner"
  gem 'shoulda', ">= 3.5"
  gem 'fabrication'
  gem 'faker'
end
