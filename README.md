```bash
# install rails and init pj
gem install rails
# excluding default testing framework
rails new twitter-clone -T -d mysql --css tailwind

# install devise
rails generate devise:install
rails g devise user
rails db:migrate
rails db:test:prepare

# install rspec
# https://github.com/rspec/rspec-rails/tree/6-0-maintenance
rails generate rspec:install

```