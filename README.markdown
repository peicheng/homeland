A new style forum for small communitys.
Support for Twitter, Facebook, Google, Github account login.

## Install

  * You need install *Ruby 1.9.2*, *Rubygems* and *Rails 3.1* first.
  * Install *Redis*, *MongoDb* 

Install thought this commands:    

  ```
  cp config/config.yml.default config/config.yml
  cp config/mongoid.yml.default config/mongoid.yml
  cp config/redis.yml.default config/redis.yml
  bundle install
  bundle update rails
  rake assets:precompile
  rails s
  ```

## Try it first.

[Demo App](http://put.im)

## Contributors

* [Jason Lee](http://github.com/huacnlee)
* [Qiu Yun](http://github.com/qiuyun8m)

Thanks [Twitter Bootstrap](http://twitter.github.com/bootstrap) and [V2EX](http://v2ex.com)
