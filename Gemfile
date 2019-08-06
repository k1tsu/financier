
source "https://rubygems.org"

gem "utopia", "~> 2.5"
# gem "utopia-gallery"
# gem "utopia-analytics"

gem "rake"
gem "bundler"

gem "rack-freeze", "~> 1.2"

gem "relaxo", "~> 1.3"
gem "relaxo-model", "~> 0.15.0"

gem 'rugged', git: 'git://github.com/libgit2/rugged.git', submodules: true
gem "tty-color"

gem "trenni-formatters", "~> 2.4"

gem "periodical", "~> 1.0"
gem "latinum", "~> 1.3"

gem "time-zone", "~> 1.1"

gem "ofx", "~> 0.3"
gem "qif", "~> 1.1"

gem "sanitize"
gem "kramdown"
gem "bcrypt", "~> 3.0"

gem "tty-prompt"
gem "rainbow"

group :test do
	gem "covered"
end

group :development do
	# For `rake server`:
	gem "guard-falcon", require: false
	gem 'guard-rspec', require: false

	# For `rake console`:
	gem "pry"
	gem "rack-test"

	# For `rspec` testing:
	gem "rspec"
end

group :production do
	# Used for passenger-config to restart server after deployment:
	gem "passenger"
end
