source 'https://rubygems.org'

gem 'sinatra'
gem 'sinatra-asset-pipeline'
gem 'slim'

gem 'bootstrap', '~> 4.1.1'

group :development do
  gem 'thin'
  gem 'capistrano', require: false
  gem 'capistrano-bundler', require: false
  gem 'capistrano-rvm', require: false
  gem 'capistrano3-puma', require: false
  gem 'sshkit-sudo', require: false
end

group :production do
  gem 'puma'
end
