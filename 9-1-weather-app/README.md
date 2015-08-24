# Weather App

## Objectives

After completing this assignment, you should be able to:

* Demonstrate use of Promises and AJAX methods
* __Demonstrate an understanding of routing, and it's role in "single page apps"__
* Demonstrate understanding of Ember.js Routes and Components

## Details

### Deliverables

* An ember-cli project hosted on Divshot
* An Issue in the Assignments Repo
* A repo containing up to date code
* A Pull Request (or more than one) containing developed features

### Requirements

* No JSHint warnings or errors

## Normal Mode

- [ ] Create an app that uses your device/computer's geolocation, and makes a request to Forecast.io with that (lat,lng) and any search parameters.
- [ ] Read the Forcast.io API Documentation and 

- You should wireframe and design a basic layout before starting this app.
- Your app should use HTML/SCSS (with Bourbon and Neat) extensively for styling (yes this is a major part of this application) - Do not use Materialize or Bootstrap, you can use icon sets or photos from other sites.
- You should use the Ember.js Router and Routes to represent the application states. Your routes should be:
    - `http://localhost:4200/`
    - `http://localhost:4200/weather/:lat/:lng`

## Nightmare Mode

1. In addition to Normal Mode, give your app an extra search bar that allows you to search for weather in other cities around the world.
2. Use Firebase and Firebase Authentication to sign in a user and store their favorite locations
