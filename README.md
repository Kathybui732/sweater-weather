# README

Sweater Weather is a back-end application designed to satisfy wireframes presented by a front end team. The wireframes are provided below.

This application designs endpoints

* Heroku Deployment
[Come checkout our application and docs!](https://sweater-weather-732.herokuapp.com/)

* How to start running the application
1. `git clone git@github.com:Kathybui732/sweater-weather.git`
1. `cd sweater_weather`
1. `bundle install`
1. `rails db{create,migrate}`
1. Add your own API keys to the application.yml file (WEATHER_API_KEY, UNSPLASH_API_KEY, MAPQUEST_API_KEY)
1. `bundle exec rspec` to run the test suite

* APIs utilized
1. [Unsplash](https://api.unsplash.com/)
1. [MapQuest](http://open.mapquestapi.com)
1. [Open Weather Map](https://api.openweathermap.org)

* Ruby version
Ruby 2.5.3
Rails 5.2.4

* Known issues
1. The code written for the /road_trip endpoint needs to be refactored as it is not memoizing certain API calls. This is making the app run a bit slow.

* Endpoints
Please visit the [production site](https://sweater-weather-732.herokuapp.com/) to view all endpoints!
