# <img src="https://cloud.githubusercontent.com/assets/7833470/10899314/63829980-8188-11e5-8cdd-4ded5bcb6e36.png" height="60"> MEAN/MEN stack review

### Why is this important?
<!-- framing the "why" in big-picture/real world examples -->
*This workshop is important because:*

We haven't touched MongoDB, Express, Node, and jQuery in a long time! You may not remember the roles that jQuery plays or the reason why we have Express and Node working together. What is Mongoose anyway? It's going to be important to retrieve skills and use technologies that we've studied, so we're going to practice together.

### What are the objectives?
<!-- specific/measurable goal for students to achieve -->
*After this workshop, developers will be able to:*

- Explain the role of each technology within the MEN stack.
- Give detailed account of the purpose of the different files and folders that make up a MEN/MEAN app.

### Where should we be now?
<!-- call out the skills that are prerequisites -->
*Before this workshop, developers should already be able to:*

- Build a full application in MEN, MEAN, and Ruby on Rails stacks.
- Locate course materials to help use technologies we haven't talked about in a long time.


#### Consider the following statement

*Ruby on Rails is superior to the MEAN stack because Ruby is a much more beautiful
and feature-rich language than Javascript. Rails is designed to expedite
development time because it has built in structures to facilitate CRUD and
many other common web development tasks.*

Take two minutes to write down your reaction.


#### Now, consider the following statement

*The MEAN stack is better than Rails because it is all JavaScript, the native language of the web.
Node's built in V8 JS engine makes the MEAN stack app far faster than a Ruby on
Rails app. Angular creates dynamic, single page apps which are more intuitive to write
than the `.erb` style templating of Rails apps.*

Take two minutes to write down your reaction.


## MEAN
What does MEAN mean? Without using any other resources, write down what you know about each of the following:

**MongoDB**

**Mongoose**

**Express**

**AngularJS**

**Node**

**jQuery**

After that time, find an example of 1-10 lines of code that illustrate the use of this technology.

### What is MongoDB/(Mongoose)?

* `MongoDB` is a no-SQL database.
* Generally we will not be interacting _directly_ with MongoDB, instead we'll be working with `mongoose`.
* `Mongoose` is a library or "wrapper" that gives us a bunch of convenience methods for working with MongoDB records (kind of like jQuery's convenience methods for manipulating the DOM).

### What is Express JS?
- Express is a framework built on top of Node.js that makes development of web servers more intuitive and quicker.
- Express allows us to easily set up routes that will trigger actions such as rendering pages or returning JSON.

### What is AngularJS

From the [Angular Guide Introduction](https://docs.angularjs.org/guide/introduction):

* A "framework for dynamic web apps"
* "Lets you use HTML as your template language" and helps you "extend HTML's syntax"
* "Handles all of the DOM and AJAX glue code you once wrote by hand and puts it in a well-defined structure"
* Is "opinionated about how a CRUD application should be built"
* Comes with "Data-binding, basic templating directives, form validation, routing, deep-linking, reusable components and dependency injection"
* "Angular simplifies application development by presenting a higher level of abstraction to the developer"
* "Not every app is a good fit for Angular. Angular was built with the CRUD application in mind."


### What is Node?
- Node.js is a webserver that operates on the V8 Google Chrome JavaScript runtime, allowing you to write server-side code in JavaScript.
- Node.js provides the ability to handle requests and issue responses.
- It is fast.
- It is fast largely because it is asynchronous, meaning code can run in parallel without "blocking" the call stack (the list of other concurrent commands).


# Tunely revisit

Go to the codebase from the [original Tunely app on the `solutions_sprint_6` branch](https://github.com/sf-wdi-31/tunely/tree/31/solutions_sprint_6). You will be assigned to a file within that project from this list:

* `package.json`/`bower.json`
* `server.js`
* `models/*`, especially `models/index.js`
* `controllers/albumsController.js`
* `controllers/albumsSongsController.js`
* `controllers/apiController.js` and `controllers/index.js`
* `public/scripts/app.js`
* `public/styles/style.css` and `public/images/*`


Let's investigate these pieces and answer the following questions:

1. Is this server-side code or client side code? How do you know?
1. What part of the stack does this represent? What technologies are present here (HTML, CSS, middleware, JavaScript, etc.)?
1.  What is this piece of the application (file or directory) responsible for?
1. What lines of code are most important for understanding how this works?
1. What 3-5 lines of code are difficult to understand at first glance? After a closer look, what does that code do?


Once you've written something out, taken the key screenshots (`cmd`+`shift`+ `4`), and gathered all the info you want to show us, please put your responses on [this google doc](https://docs.google.com/document/d/19piRsY8R6wwtjD9ET9XiyCrBITvaRVuBNpWAV2jk6-U/edit). We'll each present 2-5 minutes on the piece we investigated to refresh the class on what it does.


# `tunely-angular` app

Let's check out the [`tunely-angular` sprint 5 solutions branch](https://github.com/SF-WDI-LABS/tunely-angular/blob/master/docs/sprint5.md) as a subject for contrasting MEN and MEAN stack.

Let's investigate the pieces we just saw in the MEN version and answer the following question:

* What's the difference between this version and the MEN version you explored just a moment ago?


## Resources:
* [An intro to Mongo/Express/Node from WDI25](https://github.com/SF-WDI-LABS/shared_modules/tree/master/03-angular-mean/intro-mean/25)
