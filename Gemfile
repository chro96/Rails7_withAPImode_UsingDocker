source "https://rubygems.org"
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby "3.2.2"
gem "rails", "~> 7.0.4", ">= 7.0.4.3"
gem "mysql2", "~> 0.5"
gem "puma", "~> 5.0"
gem 'active_model_serializers'
gem 'puma', '~> 5.0'
gem 'rack-cors'
gem 'rswag-api'
gem 'rswag-ui'
gem 'seed-fu', '~> 2.3'
# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem "tzinfo-data", platforms: %i[ mingw mswin x64_mingw jruby ]

# Use Rack CORS for handling Cross-Origin Resource Sharing (CORS), making cross-origin AJAX possible
# gem "rack-cors"

group :development, :test do
  # See https://guides.rubyonrails.org/debugging_rails_applications.html#debugging-with-the-debug-gem
  gem "debug", platforms: %i[ mri mingw x64_mingw ]
end

group :development do
  # Speed up commands on slow machines / big apps [https://github.com/rails/spring]
  # gem "spring"
end


group :development, :test do
  gem 'bullet'
  gem 'debug', platforms: %i[mri mingw x64_mingw]
  gem 'factory_bot_rails'
  gem 'faker'
  gem 'gimei'
  gem 'pry-byebug'
  gem 'pry-stack_explorer'
end

group :production, :staging do
end

group :development do
  gem 'annotate'
  gem 'brakeman'
  gem 'rubocop', require: false
  gem 'rubocop-performance'
  gem 'rubocop-rails'
end

group :test do
    # 必要なのか後ほど検証
  gem 'json-schema_builder'
  gem 'rspec-rails'
  gem 'rswag-specs'
  gem 'timecop'
end
