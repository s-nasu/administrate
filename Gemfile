source 'https://rubygems.org'

gemspec

gem "administrate-field-image"
gem "autoprefixer-rails"
gem "bourbon", "~> 5.0.0.beta.7"
gem "faker"
gem "pg"
gem "redcarpet"
gem "sentry-raven"
gem "unicorn"
gem "actionpack", "~> 5.1.0"
gem "actionview", "~> 5.1.0"
gem "activerecord", "~> 5.1.0"
gem "rails-controller-testing"

group :development, :test do
  gem "appraisal"
  gem "awesome_print"
  gem "bundler-audit", :require => false
  gem "byebug"
  gem "dotenv-rails"
  gem "factory_girl_rails"
  gem "i18n-tasks"
  gem "pry-rails"
  gem "rspec-rails", "~> 3.5.0"
end

group :test do
  gem "ammeter"
  gem "database_cleaner"
  gem "formulaic"
  gem "launchy"
  gem "poltergeist"
  gem "shoulda-matchers", "~> 2.8.0", :require => false
  gem "timecop"
  gem "webmock"
end

group :staging, :production do
  gem "rack-timeout"
  gem "rails_stdout_logging"
  gem "uglifier"
end
