# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version
# ruby -v
# Output: ruby 2.6.3pxx (20xx-xx-xx revision xxxxx) 
* System dependencies
 # sudo apt-get install curl git nodejs gcc make libssl-dev libreadline-dev zlib1g-dev libsqlite3-dev
* Configuration
 # git clone https://github.com/rbenv/rbenv.git ~/.rbenv
 # echo 'export PATH="$HOME/.rbenv/bin:$PATH"' >> ~/.bashrc
 # echo 'eval "$(rbenv init -)"' >> ~/.bashrc
 # source ~/.bashrc
 # mkdir -p "$(rbenv root)"/plugins
 # git clone https://github.com/rbenv/ruby-build.git "$(rbenv root)"/plugins/ruby-build
 # rbenv -v
 # rbenv 1.1.2-2-g4e92322
 # rbenv install 2.6.3 --verbose
 # rbenv global 2.6.3
* Database creation

* Database initialization

* How to run the test suite
# rails server
 # http://localhost:3000/cars
* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions
# gem install rails
# mkdir odin_on_rails
# cd odin_on_rails
# rails new my_first_rails_app
# cd my_first_rails_app
# rails generate scaffold car make:string model:string year:integer
# rails db:migrate
* ...
test