# Blank Rails app

An alternative to the Rails command. Contains basic stuff such as user authentication, static pages etc. that you're most likely 
going to need in all of your applications.

## TODO when creating a new app

* Run rake app:init. It creates config/database.yml and config/settings.yml. It also creates a users.yml fixture, with an
  appropriately salted password hash. Then, it runs rake db:migrate.
* Run rake test to make sure all the tests pass.

## Static pages

Static pages is created as views in app/views/pages. A route (and the pages controller) maps /foo to these static pages. Creating app/views/pages/about.html.erb gives you /about.

The root of the app is by default app/views/pages/index.html.erb.

## Form builder and form fields

Description here.

## jQuery

Description here.

## User authentication

Description here.

* Signing up (no validation through e-mails though)
* Password recovery

# License

Released under the MIT license.