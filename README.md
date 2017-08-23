CherryTomato
---

http://cherrytomato.herokuapp.com/

A time organizer based on the Pomodoro technique.

<img src="https://github.com/yahmds/CherryTomato/blob/master/assets/images/cherrytomato.png" width="200">

[![Build Status](https://travis-ci.org/yahmds/CherryTomato.svg?branch=master)](https://travis-ci.org/yahmds/CherryTomato)

## Installation
- You need Ruby 2.3+, and bower.

- Install the needed gems and bower componenets by running `bundle install` and `bower install`.

- Create a file named `settings.rb` and add your env variables there.
  An example is provided in `settings.example.rb`.

- For the first time, you want to setup the database, run
  `./run_migrations` to create the database and the tables needed.
  A PostgreSQL server must be running.

- Run the server using `rackup -p 7777` or provide another port number.

## Contribution
If there's anythong you want to change, please send a pull request.

## License
See [LICENSE](https://github.com/yahmds/CherryTomato/blob/master/LICENSE).
