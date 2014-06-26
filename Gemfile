# encoding: utf-8

source 'https://rubygems.org'

gemspec

group :test do
  gem 'mime-types', '~> 1.25', :platforms => [:jruby]
end

group :development, :test do
  gem 'devtools', git: 'https://github.com/rom-rb/devtools.git'
end

eval_gemfile 'Gemfile.devtools'
