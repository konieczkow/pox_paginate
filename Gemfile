source "http://rubygems.org"

gem 'activeresource', '~> 3.0.1'
gem 'activesupport', '~> 3.0.1'
gem 'will_paginate', '~> 3.0.pre2'

group :test do
  gem 'activerecord',  '~> 3.0.1'
  gem 'rspec', '~> 2.0.0'
  gem 'nokogiri', '~> 1.4.3.1'
  platforms :jruby do
    gem 'jdbc-sqlite3', '~> 3.6.3.054'
    gem 'activerecord-jdbcsqlite3-adapter', '~> 0.9.7'
  end
  platforms :ruby do
    gem 'sqlite3-ruby', '~> 1.3.1'
    gem 'libxml-ruby', '~> 1.1.4' unless Object.const_defined?('RUBY_ENGINE') && RUBY_ENGINE =~ /rbx/
  end
end