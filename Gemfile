source 'http://rubygems.org'

gemspec

#gem 'neo4j-core', :path => '../neo4j-core'

#gem 'orm_adapter', :path => '../orm_adapter'

gem 'coveralls', require: false

gem 'activesupport'

group 'development' do
  gem 'pry'
  gem 'os' # for neo4j-server rake task
  gem 'rake'
  gem 'yard'
end

group 'test' do
  gem "rspec", '~> 2.0'
  # gem 'rspec-its' instead of its in rspec 3
  gem "its"
  gem "test-unit"
end
