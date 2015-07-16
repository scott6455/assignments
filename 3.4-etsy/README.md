# Etsy

## Objectives

After completing this assignment, you should be able to:

* Demonstrate understanding of application state vs UI
* Demonstrate use of documented function
* Demonstrate ability to use Handlebars.js
* Demonstrate knowledge of callbacks
* Demmontrate ability to break existing site into partials and templates

## Setup

```sh
# cd into week directory
# then hub clone tiy-lr-fee-2015-June/3.4-etsy
# then hub create to create the repo on Github, too
# run npm install
# run bower install
# DO WORK
```

## Deliverables

* A publicly visible website (gh-pages, divshot, heroku, etc...)

## Normal Mode

You're going to create an application that:
Re-Create An Etsy Page - https://www.etsy.com/search?q=whiskey

> Specifically you need to focus on the sidebar and the main content of items. 

* Utilize the data for whatever search term you use - [DATA
   HERE](https://api.etsy.com/v2/listings/active.js?api_key=cdwxq4soa7q4zuavbtynj8wx&keywords=whiskey&includes=Images,Shop&sort_on=score)
* Use Bourbon / Neat to help you out (optional, but suggested)
* You are free to change the search term to whatever you'd like.
* We haven't covered how to fetch data using JavaScript, so follow the instructions to use `loadEtsy`
* Everything should be styled as closely as possible, including the Header/Footer
* You should implement hover events and link the items to their proper Etsy product pages
* Unless you do the bonus question #2, you can just put random links in your sidebar.
* Do not use jQuery - we haven't covered it so this SHOULDN'T be a problem
* Also, no need to make any of the form elements work.

## Hard Mode

Everything above plus:

* Create your own API token by signing up as an [Etsy developer](https://www.etsy.com/developers/)
* Replace the API token in `load-etsy.js`
* Pull the categories from the data to create the sidebar, with links that filter the listings.
* Use `onsubmit` on form elements so that the main area is switched out when a user submits the search form but it doesn't reload the entire page.
* Implement loading spinners while data is loading (you can use the `immediate` argument of `loadEtsy` to do this)
* Implement the sorting dropdown.

## Fetching data from Etsy

The project skeleton includes a function called `loadEtsy`.
This accepts three arguments:

* `query` - The keyword on etsy that you want to search for
* `onload` - A function that will be run once the API returns data. This will pass back the JSON returned by the Etsy API
* `immediate` - A callback that is run immediately, this can be used for things like loading spinners or other fun things...
