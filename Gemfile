source 'https://rubygems.org'
gemspec

group :test do
  gem 'rake', '>= 0.8.7'
  gem 'json', '1.8.0'
  gem 'simplecov'
  gem 'test-unit', :platform => [:mri_20, :mri_21, :mri_22]
end

group :profile do
  gem 'ruby-prof'
end

platforms :rbx do
  gem 'rubysl'
  gem 'rubysl-test-unit'
  gem 'racc'
  gem 'rubinius-coverage',  '~> 2.0'
end
