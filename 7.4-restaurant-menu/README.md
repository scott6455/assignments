# Restaurant

## Description
A dynamic restaurant page

## Objectives

### Learning Objectives

After completing this assignment, you should:

- Understand how to design and execute a frontend application given ambiguous requirements by a client.
- Understand how all of the pieces of Backbone fit together to create a dynamic frontend application.

### Performance Objectives

After completing this assignment, you should be able to:

- Create wireframes, outline of responsibilites, and plan of attack as needed as part of the planning process when making a complex frontend application.
- Execute client requirements to make a complete application.

## Details

### Deliverables

* A publicly available build of your site on Github pages

### Requirements

* No JSHint warnings or errors

## Normal Mode
Imagine Bangkok Thai Cuisine has come to you and asked you to help them build a web presence.
They don't know anything
about the Internet, but they know they need a web page and a way for users to order online.
They want an interactive menu that displays all of their food choices with prices, descriptions, etc.
They want the customer to be able to select menu items and create an order
with a total price. When the user saves the order, it should `console.log` the 

Create a Backbone.js app, using the tiny-lr server, to create a dynamically
updating menu page.
See Additional Resources below for an example online menu.
For normal mode you can immediately add an item to the order instead of having a comments or asking how many should be in the order.

### Tasks
#### Getting Started
- [ ] Setup the scaffolding and install Backbone
- [ ] Setup templates for the different dynamic portions of the application
- [ ] Produce static data for the menu items
- [ ] Produce a functional static mockup

#### Menu
- [ ] Fetch and `console.log` the static JSON for the menu items
- [ ] Render a template for each menu item, not according to category
- [ ] Define a FoodListView
- [ ] Make a view instance responsible for each item instead of just a template for the collection
- [ ] Define a FoodItemView
- [ ] `console.log` the food model when I click on its price button
- [ ] Define an OrderItem Model
- [ ] Define an Order Collection
- [ ] Create an instance of Order
- [ ] Pass the order to the child views
- [ ] `console.log` the order when I click on the foods price
- [ ] Add the food model to the order
- [ ] Define a FoodCategoryView constructor
- [ ] Make instances of FoodCategoryView for each category
- [ ] Make a instance of FoodCategoryView for popularity

#### Order view
- [ ] Define an OrderView constructor
- [ ] Render an instance of OrderView
- [ ] In OrderView, `console.log` the order
- [ ] In OrderView, `console.log` a food model every time a food model is added to the order
- [ ] Render the data from the order every time the order is updated
- [ ] In your OrderView, define a `subtotal` function that calculates the total price.
- [ ] `console.log`, then render, every time the order is updated


#### Order data
- [ ] Save the order data to Parse when the order is submitted

## Hard Mode
- When a user submits an order, make a POST request to `/collections/<initials>-order` with an array of ids for all the items a user has ordered
- Using Backbone's built in [validation](http://backbonejs.org/#Model-validate), make sure that a user cannot submit an empty order

## Additional Resources
- [Example](https://eatstreet.com/angel-thai-cuisine/menu)
- [Order Up](https://orderup.com/restaurants/nuvo-burrito/delivery/categories/0)
