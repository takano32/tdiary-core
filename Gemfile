source :rubygems

gem 'rack'
gem 'rake'
gem 'sprockets'
gem 'coffee-script'

gem 'redcarpet'

group :development do
  gem 'thin', :require => false, :platforms => :ruby
  gem 'racksh', :require => false

  gem 'capistrano', :require => false
  gem 'capistrano_colors', :require => false
  gem 'pit', :require => false

  group :test do
    gem 'tapp'

    gem 'test-unit', :require => 'test/unit'
    gem 'rspec'

    gem 'capybara', :require => 'capybara/rspec'
    gem 'capybara-mechanize', '~> 0.3.0.rc3', :require => 'capybara/mechanize'
    gem 'launchy'

    gem 'rcov', :platforms => :mri_18
    gem 'simplecov', :require => false, :platforms => :mri_19
  end
end
