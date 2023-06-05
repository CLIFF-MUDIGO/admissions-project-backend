source "https://rubygems.org"

# An object-relational mapper
# https://guides.rubyonrails.org/active_record_basics.html
gem "activerecord"
gem "thin"
# Configures common Rake tasks for working with Active Record
# https://github.com/sinatra-activerecord/sinatra-activerecord
gem "sinatra-activerecord"
gem "rack-cors"
gem "rack-contrib"

# Run common tasks from the command line
# https://github.com/ruby/rake
gem "rake"
gem "psych", '~> 4.0.0'
# Provides functionality to interact with a SQLite3 database
# https://github.com/sparklemotion/sqlite3-ruby


# Require all files in a folder
# https://github.com/jarmo/require_all
gem "require_all"
gem "faker"
gem "uri"
# These gems will only be used when we are running the application locally
group :development do
  gem "pry"
  gem "sqlite3", "~> 1.4"
  gem "rerun"
end
group :production do
  gem "pg"
end
