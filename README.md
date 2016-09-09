# README

## Ruby on Rails "toy_app"

This is the second application for the
[*Ruby on Rails Tutorial*](http://www.railstutorial.org/)
by [Michael Hartl](http://www.michaelhartl.com/).

## Heroku installation

Don't forget to modify the `root` of your rail application.

```
$ heroku create
$ git push heroku master
$ heroku run rake db:migrate
```

## Updating process

### Rails process

Don't forget to update your database if modified using `rails db:migrate`!

### Git process

```
$ git add -A
$ git commit -am "Your Ref"
$ git push
$ heroku run rake db:migrate
$ git push heroku master
```
