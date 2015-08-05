# Blog Comments

## Description

Create a blog comment widget using Handlebars, Backbone, and jQuery.
This should store and sync to the `tiny-lr` server in a collection named `rt-comments` where you would replace `rt` with your initials.

While not 100% the same look at the discourse comments on my blog:
http://ryantablada.com/post/how-destiny-has-killed-its-base-game-to-dlc-growth

## Objectives

### Learning Objectives

After completing this assignment, you should
- Understand how to create and describe Backbone Models, Collections, and Views
- Understand how to separate Application, Model, and View code

### Performance Objectives

After completing this assignment, you be able to effectively use

* Backbone.Events
* Backbone.Model
* Backbone.Collections
* Backbone.View

## Details

### Deliverables

* A build on Github Pages with link in your Issue

### Requirements

* No JSHint warnings or errors
* No JSCS warnings or errors
* Separate files for views vs models vs application code

### Normal Mode

* Show button that says "add comment"
* On button click show form to create comment
  - Should ask for email, comment string, and any other fields you feel like
* Allow user to submit a comment
* Clear & hide the form after comment is sumbitted
* Show all existing comments after the "add comment" button/comment form

### Hard Mode

* Add an up and down vote function to your comments (ala Youtube)
  - Should show blue number for up votes > down votes
  - Should show red number for down votes > up votes

## Additional Resources

- [Backbone Docs](http://backbonejs.org/)
- [Underscore Docs](http://underscorejs.org/)
- [jQuery Docs](https://api.jquery.com/)
