# github-api-profile

## Description


## Objectives

### Learning Objectives

After completing this assignment, you should:

* Be able to breakdown a complex sequence into a series of steps, use jQuery AJAX, handle callbacks and asynchronous code, and write to the DOM with JS

### Performance Objectives

## Details

### Deliverables

* A publicly visible website on `gh-pages`

### Requirements

* No JSHint warnings or errors
* No JS errors in the browser
* All functions and code should work according to the following description.
* Personalized plan of attack

## Normal Mode

Build a github profile app that prints out some info from the Github API and your repos. __For the design, you should recreate the Github Repos Tab to the best of your ability__.

> Github tab page: https://github.com/rtablada?tab=repositories

The information from the Github API that you will display includes information from your github user account and repositories.

- Write `$.ajax()` requests to:
    - `https://api.github.com/users/<username>`
    - `https://api.github.com/users/<username>/repos`

- After loading data from the Github API, write at least the following information to the DOM:
    - name
    - blog
    - location
    - email
    - avatar_url
    - html_url
    - and list all of your repositories

### Tasks
- [ ] Read and interact with the examples in [jQuery Fundamentals: AJAX &
  Deferreds](http://jqfundamentals.com/chapter/ajax-deferreds)
- [ ] Watch the video [What the heck is the event loop
  anyway?](https://www.youtube.com/watch?v=8aGhZQkoFbQ)

## Nightmare Mode

Implement the Contributions tab of your profile page.
This can be implemented as a separate set of `html` and `js` (you'll probably want to share your `css` to a good point).

## Documentation Test Mode

Deploy a [gatekeeper](https://github.com/prose/gatekeeper) to allow anyone to
log into the app and view their profile.
This is a test of reading documentation and figuring things out.

## Notes


## Additional Resources
- https://octicons.github.com/
- [Understanding the JS event loop](http://latentflip.com/loupe)
- [Postman Chrome
  app](https://chrome.google.com/webstore/detail/postman-rest-client/fdmmgilgnpjigdojojpjoooidkmcomcm?hl=en)
