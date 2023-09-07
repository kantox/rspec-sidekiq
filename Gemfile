source 'https://rubygems.org'

platforms :rbx do
  gem 'psych'
  gem 'rubinius-developer_tools'
end

gem 'sidekiq', "~> #{ENV.fetch('SIDEKIQ_VERSION')}"
gem 'activejob', "~> #{ENV.fetch('SIDEKIQ_VERSION')}"
gem 'actionmailer', "~> #{ENV.fetch('RAILS_VERSION')}"
gem 'activerecord', "~> #{ENV.fetch('RAILS_VERSION')}"
gem "activemodel", "~> #{ENV.fetch('RAILS_VERSION')}"
gem "railties", "~> #{ENV.fetch('RAILS_VERSION')}"

gemspec
