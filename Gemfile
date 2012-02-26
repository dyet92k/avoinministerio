source 'http://rubygems.org'

gem "rails", "3.1.3"

# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem "coffee-rails", "~> 3.1.1"
  gem "sass-rails",   "~> 3.1.5"
  gem "uglifier",     ">= 1.0.3"
end

gem "devise"
gem "haml-rails"
gem "i18n_routing"
gem "jquery-rails"
gem "omniauth-facebook"
gem "rails-i18n"
gem "redcarpet"
gem "simple_form"
gem "state_machine"

gem "rspec-rails", :groups => [ :development, :test ]

group :development do
  gem "rails-erd"
  gem "sqlite3"
  gem "thin"
end

group :production do
  gem "pg"
end

group :test do
  gem "capybara"
  gem "database_cleaner"
  gem "factory_girl_rails", "1.4.0", :require => false
  gem "rb-fsevent", :require => false if RUBY_PLATFORM =~ /darwin/i
  gem "shoulda-matchers"
  gem "spork", "> 0.9.0.rc"
  gem "turn", "~> 0.8.3", :require => false
end
