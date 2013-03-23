source 'https://rubygems.org'

gem 'rails', '3.2.12'
# CSSフレームワーク
gem 'bootstrap-sass', '2.1'
# パスワードを暗号化する
gem 'bcrypt-ruby', '3.0.1'

# Bundle edge Rails instead:
# gem 'rails', :git => 'git://github.com/rails/rails.git'

# postgresql
gem 'pg', '0.12.2'

group :development, :test do
  gem 'rspec-rails', '2.11.0'
  # テストを自動化
  gem 'guard-rspec', '1.2.1'
  # テストを高速化
  gem 'spork', '0.9.2'
  gem 'guard-spork', '1.4.2'
end

# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails',   '~> 3.2.5'
  gem 'coffee-rails', '~> 3.2.2'

  # See https://github.com/sstephenson/execjs#readme for more supported runtimes
  # gem 'therubyracer', :platforms => :ruby

  gem 'uglifier', '>= 1.2.3'
end

gem 'jquery-rails', '2.0.2'

group :development do
  # モデルに注釈をつけるGem
  gem 'annotate', '2.5.0'
end

group :test do
  # ウェプアプリケーションでの利用者の振る舞いを真似ることが可能に
  gem 'capybara', '1.1.2'
  # Guardを利用するための前提gem
  gem 'rb-fsevent', '0.9.1', :require => false
  # Mac OS Xに通知するgem
  gem 'growl', '1.0.3'
  # Fixturesを利用することなくテストのためのモデルオブジェクトを生成するgem
  gem 'factory_girl_rails', '4.1.0'
  # 受け入れテストのためのテスティングフレームワーク
  gem 'cucumber-rails', '1.2.1', :require => false
  # テスト終了時にデータベースをきれいにする
  gem 'database_cleaner', '0.7.0'
end

# To use ActiveModel has_secure_password
# gem 'bcrypt-ruby', '~> 3.0.0'

# To use Jbuilder templates for JSON
# gem 'jbuilder'

# Use unicorn as the app server
# gem 'unicorn'

# Deploy with Capistrano
# gem 'capistrano'

# To use debugger
# gem 'debugger'
