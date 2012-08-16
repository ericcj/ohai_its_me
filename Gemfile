# for missing encoding in ancient httpauth gem (transitive dependency)
if RUBY_VERSION =~ /1.9/
  Encoding.default_external = Encoding::UTF_8
  Encoding.default_internal = Encoding::UTF_8
end

source 'http://rubygems.org'

gem 'rails', '3.1.4'

# Bundle edge Rails instead:
# gem 'rails',     :git => 'git://github.com/rails/rails.git'

gem 'pg'

gem "render_or_redirect", :git => 'git@github.com:becarella/render_or_redirect.git'
gem 'let_me_in', :git => 'git://github.com/ericcj/let_me_in.git', :branch => 'forked_stuff'
gem 'navel_gazer', :git => 'git://github.com/ericcj/navel_gazer.git', :branch => 'forked_stuff'

gem 'omniauth-identity'
gem 'omniauth-instagram'
gem 'omniauth-twitter', '0.0.8'
gem 'omniauth-banters', :git => "git://github.com/becarella/omniauth-banters.git"
gem 'omniauth-foursquare'
gem 'omniauth-tumblr'
gem 'omniauth-lastfm'

gem 'handlebars_wax', :git => 'git@github.com:goggin13/handlebars_wax.git'
gem 'handlebars_assets', :git => 'git@github.com:goggin13/handlebars_assets.git'

# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails',   '3.1.4'
  gem 'coffee-rails', '~> 3.1.1'

  # See https://github.com/sstephenson/execjs#readme for more supported runtimes
  # gem 'therubyracer'

  gem 'uglifier', '>= 1.0.3'
end

gem 'jquery-rails'

# To use ActiveModel has_secure_password
# gem 'bcrypt-ruby', '~> 3.0.0'

# Use unicorn as the web server
# gem 'unicorn'

# Deploy with Capistrano
# gem 'capistrano'

# To use debugger
# gem 'ruby-debug19', :require => 'ruby-debug'

group :test do
  # Pretty printed test output
  gem 'turn', '0.8.2', :require => false
end
