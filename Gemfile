source "https://rubygems.org"
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby "3.2.0"

gem "rails", "~> 7.0.8", ">= 7.0.8.7"
gem "sprockets-rails"
gem "sqlite3", "~> 1.4"
gem "puma", "~> 5.0"
gem "importmap-rails"
gem "turbo-rails"
gem "stimulus-rails"
gem "jbuilder"
gem 'ancestry'
# Windows用タイムゾーンデータ
gem "tzinfo-data", platforms: %i[ mingw mswin x64_mingw jruby ]

# 起動高速化（bootsnapが原因ならコメントアウト）
gem "bootsnap", require: false

# ---- 不要な開発用Gemを削除またはコメントアウト ----
# group :development, :test do
#   gem "debug", platforms: %i[ mri mingw x64_mingw ]
# end

group :development do
  # gem "web-console"
  # gem "rack-mini-profiler"
  # gem "spring"
end

group :test do
  gem "capybara"
  gem "selenium-webdriver"
end
