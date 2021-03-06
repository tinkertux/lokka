source 'https://rubygems.org'

gem 'bundler'
gem 'rack'
gem 'rack-flash', '~> 0.1.2'
gem 'sinatra-flash', '~> 0.3.0'
gem 'i18n', '~> 0.7'
gem 'sinatra', '~> 1.4.2'
gem 'sinatra-contrib', '~> 1.4.0'
gem 'dm-core',          '~> 1.2.1'
gem 'dm-migrations',    '~> 1.2.0'
gem 'dm-timestamps',    '~> 1.2.0'
gem 'dm-validations',   '~> 1.2.0'
gem 'dm-types',         '~> 1.2.2'
gem 'dm-is-tree',       '~> 1.2.0'
gem 'dm-tags',          '~> 1.2.0'
gem 'dm-is-searchable', '~> 1.2.0'
gem 'dm-pager',         git: 'https://github.com/lokka/dm-pagination'
gem 'dm-aggregates',    '~> 1.2.0'
gem 'data_objects',     '0.10.17'
gem 'builder'
gem 'haml', '~> 5.0'
gem 'sass'
gem 'tilt', '~> 2.0'
gem 'compass'
gem 'slim', '~> 3.0.7'
gem 'rake', '~> 11.0'
gem 'erubis', '~> 2.7.0'
gem 'activesupport', '~> 4.2'
gem 'nokogiri'
gem 'tux'
gem 'padrino-helpers', '~> 0.14.1.1'
gem 'coderay', '1.0.5'
gem 'kramdown'
gem 'RedCloth', '4.2.9'
gem 'wikicloth', '0.8.3'
gem 'redcarpet'
gem 'yard-sinatra', '1.0.0'
gem 'backports', '2.3.0'
gem 'coffee-script'
gem 'request_store'
gem 'aws-sdk-s3'
gem 'mimemagic'

Dir["public/plugin/lokka-*/Gemfile"].each {|path| eval(open(path) {|f| f.read }) }

group :production do
end

group :development, :test do
  gem 'tapp', '1.3.0'
end

group :development do
  gem 'dm-sqlite-adapter', '1.2.0'
end

group :test do
  gem 'dm-transactions', '~> 1.2.0'
  gem 'rack-test', '0.6.1', require: 'rack/test'
  gem 'rspec', '2.14.1'
  gem 'simplecov', require: false
  gem 'factory_girl', '~> 4.0'
  gem 'database_cleaner', '0.7.1'
end

group :mysql do
  gem 'dm-mysql-adapter', '1.2.0'
end

group :postgresql do
  gem 'dm-postgres-adapter', '1.2.0'
end
