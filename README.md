
# README

A super simple rails applicaton created with [create-rails-app](https://github.com/la-ruby/create-rails-app)<br>
[demo](https://created-rails-app.herokuapp.com/posts)

## Quickstart

supose you're building a new application named example-app

```
cd ~
git clone git@github.com:la-ruby/created-rails-app.git
mv created-rails-app example-app
cd example-app
./bin/rename_app ExampleApp example-app example_app
git add --all && git commit -m "Customized name"
./bin/setup # covers most of ^
bundle exec rake webpacker:clobber
./bin/rails server # In a seperate tab
./bin/webpack-dev-server # In a seperate tab
# open http://localhost:3000/posts , bootstrap kitchen sink should render properly at this point.
```

