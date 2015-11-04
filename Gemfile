if ENV['USE_OFFICIAL_GEM_SOURCE']
  source 'https://rubygems.org'
else
  source 'https://ruby.taobao.org'
end


# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '4.2.4'
# Rails::API is a subset of a normal Rails application, created for applications that don't require all functionality that a complete Rails application provides
gem 'rails-api'

# Use mysql as the database for Active Record
gem 'mysql2', '0.3.20'
# user tree structure
gem 'ancestry', '~> 2.1.0'

# A set of Rails responders to dry up your application
gem 'responders', '~> 2.1.0'

# for LDAP
gem 'net-ldap', '~> 0.11'

# 分页
gem 'kaminari', '~> 0.16.3'
# 搜索表单
gem 'ransack', github: 'activerecord-hackery/ransack', branch: 'rails-4.2'
# 查询扩展
gem 'by_star', :git => "git://github.com/radar/by_star"

# 跨域
gem 'rack-cors', '~> 0.4.0'

# A simple HTTP and REST client for Ruby, inspired by the Sinatra microframework style of specifying actions: get, put, post, delete.
gem 'rest-client', '~> 1.8.0'
# a http client
gem 'httparty', '~> 0.13.5'

# To use Jbuilder templates for JSON
gem 'jbuilder', '~> 2.3.0'
# A fast JSON parser and Object marshaller as a Ruby gem. http://www.ohler.com/oj/
gem 'oj', '~> 2.12.9'

# GitHub Flavored Markdown
gem 'github-markdown', '~> 0.6.8'

# 七牛上传
gem 'qiniu', '~> 6.4.1' # '~> 6.5.0'

# 队列
gem 'sidekiq', '~> 3.4.1'

# Slack api 封装
gem 'slack-notifier', '~> 1.2.1'

# 异常监控
gem 'exception_notification', '~> 4.1.1'

# Job
gem 'delayed_job_active_record', '~> 4.0.3'

# 审计
gem 'paper_trail', '~> 4.0.0'

# Daemons provides an easy way to wrap existing ruby scripts (for example a self-written server)
# to be run as a daemon and to be controlled by simple start/stop/restart commands.
# You can also call blocks as daemons and control them from the parent or just daemonize
# the current process. Besides this basic functionality, daemons offers many advanced
# features like exception backtracing and logging (in case your ruby script crashes)
# and monitoring and automatic restarting of your processes if they crash.
gem 'daemons', '~> 1.2.3'

# Clean ruby syntax for writing and deploying cron jobs. https://github.com/javan/whenever
gem 'whenever', :require => false

# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use Unicorn as the app server
# gem 'unicorn'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development


# # Use SCSS for stylesheets
# gem 'sass-rails', '~> 5.0'
# # Use Uglifier as compressor for JavaScript assets
# gem 'uglifier', '>= 1.3.0'
# # Use CoffeeScript for .coffee assets and views
# gem 'coffee-rails', '~> 4.1.0'
# # See https://github.com/rails/execjs#readme for more supported runtimes
# # gem 'therubyracer', platforms: :ruby
#
# # Use jquery as the JavaScript library
# gem 'jquery-rails'
# # Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
# gem 'turbolinks'
# # Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
# gem 'jbuilder', '~> 2.0'
# # bundle exec rake doc:rails generates the API under doc/api.
# gem 'sdoc', '~> 0.4.0', group: :doc

# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use Unicorn as the app server
# gem 'unicorn'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development


group :development do
  # Quiet Assets turns off Rails asset pipeline log.
  gem 'quiet_assets', '~> 1.1.0'

  # A thin and fast web server
  gem 'thin', '~> 1.6.3'

  # Provides a better error page for Rails and other Rack apps. Includes source code inspection, a live REPL and local/instance variable inspection for all stack frames.
  gem 'better_errors', '~> 2.1.1'

  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug'

  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'

  # # Access an IRB console on exception pages or by using <%= console %> in views
  # gem 'web-console', '~> 2.0'
end

group :test do
  # for travis ci
  gem 'rake'
end

group :production do
  # Use Unicorn as the app server. unicorn is an HTTP server for Rack applications
  # designed to only serve fast clients on low-latency, high-bandwidth connections
  # and take advantage of features in Unix/Unix-like kernels. Slow clients should
  # only be served by placing a reverse proxy capable of fully buffering both the
  # request and response in between unicorn and slow clients.
  gem 'unicorn', '~> 4.8.3'

  # New Relic is a performance management system, developed by New Relic, Inc (http://www.newrelic.com).
  # New Relic provides you with deep information about the performance of your web application as it runs in production.
  # The New Relic Ruby Agent is dual-purposed as a either a Gem or plugin, hosted on http://github.com/newrelic/rpm/
  # gem 'newrelic_rpm', '~> 3.9.9.275'
end

group :rake do
  # Mongoid
  # gem 'mongoid', '~> 4.0.2', require: false
  # gem 'mongoid-app_settings', '~> 1.3.0', require: false
  # gem 'mongoid-enum', '~> 0.2.0', require: false
  # gem 'mongoid-tree', :git => 'git://github.com/benedikt/mongoid-tree',require: false
end

