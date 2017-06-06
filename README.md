# <img src="https://cloud.githubusercontent.com/assets/7833470/10899314/63829980-8188-11e5-8cdd-4ded5bcb6e36.png" height="60"> MEN stack review

### Why is this important?
<!-- framing the "why" in big-picture/real world examples -->
*This workshop is important because:*

We haven't touched MongoDB, Express, and Node, or even jQuery in a long time! You may not remember the roles that jQuery plays or the reason why we have Express and Node working together. What is Mongoose anyway? It's going to be important to retrieve skills and use technologies that we've studied, so we're going to practice that.

### What are the objectives?
<!-- specific/measurable goal for students to achieve -->
*After this workshop, developers will be able to:*

- Explain the role of each technology within the MEN stack.
- Give detailed account of the purpose of the different files and folders that we used to structure our MEN apps.

### Where should we be now?
<!-- call out the skills that are prerequisites -->
*Before this workshop, developers should already be able to:*

- Build a full application in MEN, MEAN, and Ruby on Rails stacks.
- Locate course materials to help use technologies we haven't talked about in a long time.


<!-- #### Consider the following statement

*Ruby on Rails is superior to the MEAN stack because Ruby is a much more beautiful
and feature-rich language than Javascript. Rails is designed to expedite
development time because it has built in structures to facilitate CRUD and
many other common web development tasks.*

Take two minutes to write down your reaction.


#### Now, consider the following statement

*The MEAN stack is better than Rails because it is all JavaScript, the native language of the web.
Node's built-in V8 JS engine makes the MEAN stack app far faster than a Ruby on
Rails app. Angular creates dynamic, single page apps which are more intuitive to write
than the `.erb` style templating of Rails apps.*

Take two minutes to write down your reaction. -->


## MEN
What are the technologies in "MEN" stack? Without using any other resources, write down what you know about each of the following:

**MongoDB**

**Mongoose**

**Express**

<!-- **AngularJS** -->

**Node**

**jQuery**

If you finish early, add an example of 1-2 lines of code that show each technology.

### What is MongoDB/(Mongoose)?

- `MongoDB` is a no-SQL, "document database." 
- Generally we will not be interacting _directly_ with MongoDB, instead we'll be working with `mongoose`.
- `Mongoose` is a library or "wrapper" that gives us a bunch of convenience methods for working with MongoDB records.

Interview question(s): 

- I see you've used PostgreSQL and MongoDB. What are some engineering tradeoffs when choosing between a document database and a more traditional relational database?   

### What is Node?
- Node.js is a webserver that operates on the V8 Google Chrome JavaScript runtime, allowing you to write server-side code in JavaScript.
- Node.js provides the ability to handle requests and issue responses.
- It is fast.
- It is fast largely because it is asynchronous and non-blocking.  In Node.js, input-output (I/O) tasks, which don't take a lot of processing time, can run in parallel.

Interview question(s):

- What are some pros and cons of Node.js's single-thread, event-loop approach?

### What is Express JS?
- Express is a framework built on top of Node.js that makes development of web servers faster for developers.
- Express allows us to easily set up routes that will trigger actions such as rendering pages or returning JSON.
- Express "wraps" Node.js features and provides middleware.

Interview question(s):

- Have you ever written custom middleware? If so, explain it. If not, explain an example of some middleware you found useful.

### What is jQuery?

- jQuery is a CLIENT-side JavaScript library.
- It provides a standard API that works across browsers for DOM manipulation, AJAX, animation, and event handling, among other features.

Interview question(s):

- The team is considering whether or not to use jQuery for our next project. It has some nice features, but it is a *large* set of files. Why have you chosen to use jQuery in the past, and what are some alternatives you considered?

### Investigate and Present: Tune.ly Revisit

Go to the codebase from the [original Tunely app on the `solutions_sprint_6` branch](https://github.com/sf-wdi-37/tunely/tree/36/solutions-sprint-6). 

* `package.json` and `node_modules/*`
* `server.js`
* `models/album.js` and `models/song.js`
* `models/index.js`
* `controllers/albumsController.js`
* `controllers/albumsSongsController.js`
* `controllers/apiController.js` and `controllers/index.js`
* `public/scripts/app.js`
* `public/styles/style.css` and `public/images/*`
* `views`


Investigate your file or directory and answer the following questions in [this google doc](https://docs.google.com/document/d/1oUZ6jpetLZSGHEOnvLM1sG3NRrP18PeSr9wbafmzHkI/edit?usp=sharing). Take screenshots (`cmd`+`shift`+ `4`) of the code you'd like to highlight, and drag the image files into the google document.  We'll each present 2-5 minutes on the piece we investigated to refresh the class on what it does.

1. Is this code most closely related to the server, the client, or the database?  How do you know?
2. What is this piece of the application (file or directory) responsible for?
3. How is this file connected to the main `server.js` file in the applciation?
4. What 3-5 lines of code are most important for understanding how this code works?
5. What 3-5 lines of code are difficult to understand at first glance? After a closer look, what does that code do?

### Closing Thoughts

What kind of project requirements would lead you to decide to use Rails instead of Node/Express? When would you choose to use Node.js and Express instead of Ruby on Rails?
