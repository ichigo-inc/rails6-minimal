# README

### Run below commands for first time after cloning the repo

```
bundle install --path=vendor/bundle
bundle exec rails webpacker:install 
yarn install --check-files
```


### Generate new app

```
rbenv local 2.7.4
# rbenv exec gem install bundler
rbenv rehash
bundle init
# Add gem 'rails', '~>6' to Gemfile 
bundle install --path=vendor/bundle
bundle exec rails new . --skip-bundle
bundle install
bundle exec rails webpacker:install 
yarn install --check-files
```
