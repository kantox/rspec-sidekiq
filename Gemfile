source 'https://rubygems.org'

platforms :rbx do
  gem 'psych'
  gem 'rubinius-developer_tools'
end

gem 'sidekiq', "~> #{ENV.fetch('SIDEKIQ_VERSION')}"
gem 'activejob', "~> #{ENV.fetch('RAILS_VERSION')}"
gem 'actionmailer', "~> #{ENV.fetch('RAILS_VERSION')}"
gem 'activerecord', "~> #{ENV.fetch('RAILS_VERSION')}"
gem "activemodel", "~> #{ENV.fetch('RAILS_VERSION')}"
gem "railties", "~> #{ENV.fetch('RAILS_VERSION')}"


# The gem is bugged/incompatible in later versions due to nokogiri conflict
# and ruby versions
#   uninitialized constant Nokogiri::HTML4
#
if ENV['RUBY_VERSION'].to_f <= 2.4
  gem "loofah", "~> 2.20.0"
  gem 'nokogiri', '~> 1.8.5'
  gem 'rspec-core', '~> 3.8'
end

gemspec
