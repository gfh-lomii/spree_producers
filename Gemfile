source 'https://rubygems.org'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?('/')
  "https://github.com/#{repo_name}.git"
end

gem 'spree', github: 'spree/spree', branch: 'master'
#gem 'sprockets', '~> 4.0.2'
gem 'rails-controller-testing'
gem 'email_validator' 

gemspec
