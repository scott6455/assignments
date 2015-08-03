## HTML/CSS/Git Intro - Iron News

### Description

One of the basic, foundational skills in being a professional web developer is the translation of a designer's mockup image into a webpage with HTML and CSS. One of the basic, foundational news portals for professional web developers is "Hacker News," which is kind of like a Reddit for the startup/design/development community with a very... *minimalist* design ethic.

Since it's so simple (there's only one image!) we're going to start off here.

At the same time, we're also going to get into the habit of frequently creating git commits as checkpoints.

### Objectives

##### Learning Objectives

After completing this assignment, you should be comfortable with

* Translating images to HTML and CSS
* Hosting static pages on GitHub
* Using git on the command line
* Best practices for committing frequently

##### Performance Objectives

After completing this assignment, you be able to effectively use

* Chrome developer tools
* GitHub
* Terminal
* git
* Sublime Text

### Details

##### Deliverables

* A Pull request including
    * `index.html`
    * A linked CSS file in the location of your choice

##### Requirements

* Valid, semantic, accessable HTML
* Valid CSS
* At least one git commit (with a message) every hour that you're working on this project
* No table layouts (you won't be able to just copy paste the HTML from hacker news)

* Hard Requirements
    * Improve the user prompts with
        - Hover states for links
    * Make the different articles "zebra striped"
* Extra Hard Requirements
    * Replace the "Login" link in the nav bar with a "Account" drop down menu that has links to "Login" and "Signup"
            
### Normal Mode

Using HTML and CSS, re-create the included image (`Iron News.png`) as a webpage. Don't worry about the text content (feel free to use an ipsum generator), but use the original image and *make your best effort* to match the dimensions and styles of original page to yours.

Right now HackerNews uses all tables and inline styles.
You are allowed to use Inspect Element to find things like background colors and sizes, but you should not use any `table` elements or `display: table` in your CSS.

### Hard Mode

The HackerNews site isn't the most user friendly site in the world.
Instead, let's make two improvements to make the page easier to use:

1. Right now there is no easy way to tell that the navigation links are ACTUALLY links.
Add hover states to make this a bit easier to see

2. Zebra Stripe the different articles listed on the page

To make it easier to see where one article ends and the next begin, you should "Zebra Stripe" the odd and even articles on the HackerNews home page.

![Zebra Striped Table](http://coffeecupweb.com/wp-content/uploads/2015/01/zebra-stripe-a-table-with-css-3.jpg)

### Extra Hard Mode

The project manager at HackerNews has decided that we want to make signing up for the site really easy to do from the home page.
So they want you to replace the existing "Login" link with a dropdown labeled "Account" which drops down to show the option to "Login" or "Signup".


### Additional Resources

* [Hacker News](http://news.ycombinator.com)
* [Meet the Ipsums](http://meettheipsums.com/)
