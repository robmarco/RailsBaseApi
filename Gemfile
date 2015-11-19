source 'https://rubygems.org'
# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '4.2.5'
# Use postgresql as the database for Active Record
gem 'pg', '~> 0.15'
# bundle exec rake doc:rails generates the API under doc/api.
gem 'sdoc', '~> 0.4.0', group: :doc

# API Build Gems
gem 'jbuilder', '~> 2.0'
gem 'rack-cors', :require => 'rack/cors'
# gem 'kaminari' 			# Pagination
gem 'bcrypt', '~> 3.1.7' # Encrypt

# gem 'paperclip' 		# Attachments and file storage
# gem 'delayed_job_active_record' # Background Job
# gem 'httparty' 			# HTTP (pushwoosh depends on it)

# Deploytment Gems
gem 'figaro' 				  # Manage Environment Vars
# gem 'puma'
# gem 'unicorn'
# gem 'capistrano-rails', group: :development

group :development, :test do
  gem 'byebug'  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'faker'
  gem 'hirb'
  # Testing
  gem 'guard-rspec', require: false
  gem 'rspec-rails', '~> 3.0'
  gem 'factory_girl_rails'
end

group :development do # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
  gem 'annotate'
  # gem 'brakeman', :require => false # Security
end

group :production do
  gem 'rails_12factor'
end



