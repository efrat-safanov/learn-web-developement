# How-To learn JavaScript and Webdevelopment
JavaScript and Webdevelopement belong together like sun and moon...
It is possible to make feature rich applications which take visibly ressources and come along with all the benefits the web provides us with. This document should show you the way how you can learn everything necessary of building apps yourself.


## Understand the sense of HTML
The HypertextMarkupLanguage is your interface to create structural and visual objects as user interface.
It is your gate to allow interactions to the enduser in the browser.
Also it is very easy to write and read and also getting supported as markup language for desktop plattforms.
Following markup examples which take great use of css class binding. 
The code snippets in the link below show how html looks to render different semantics (lists, tables).
http://twitter.github.com/bootstrap/base-css.html


## Optional: Develope your own styles with CSS
To learn CSS you can use any tutorial as there is no really bad CSS.


## Understand the basics of JavaScript
To get the basic idea of how to use JavaScript it is recommend to learn the syntax and the datatypes.
https://developer.mozilla.org/en-US/docs/JavaScript/Guide/Values,_variables,_and_literals
Go through the mozilla guide and test each example yourself in your browser console.


## Use JavaScript to make your application interactive
To give your static HTML page some dynamic behaviour use structured View objects.
Read through the backbonejs docs: http://backbonejs.org
Try to understand this example: http://backbonejs.org/examples/todos/index.html


## Give your application more scale with higher tools
When writing own applications in the step before you will notice that there are some limits.
In this step we will break this limits and push our know-ledge to a new level.
To accomplish this we will use node.js to server our files and modularize our front-end files with requirejs.

### Static file serving with expressjs
Checkout this example: https://github.com/visionmedia/express/blob/master/examples/static-files/index.js
Checkout the api of express: http://expressjs.com/api.html
Try to server your front-end files with these ressources.

### Modularize your application with requirejs
As you maybe mentioned it is hard to keep code clean in the front-end.
It is hard to use a single file for each Backbone class because you always have to add a script declaration.
With requirejs you can put each class, object, prototype in one file and set is dependencies.
Checkout: http://requirejs.org
It is quite hard to find good tutorials with requirejs.
Try to find out how to use require.config and how a simple module is build up with define.
Also check out the text plugin to load templates. The rest should be possible on your own.


## Add some controller actions to expressjs
Until now we only used express for serving our static files but we can use expressjs for more!
Try to serve data from an expressjs request listener to the client (e.g. Backbone.Model).
The data can be stored in a file our straight forward with a database (MongoDB).


## Gain experience
Until here you can do everything you need for simple projects.
Try now to gain experience by working on some projects of your own maybe you run in situation which are new for you.


## Learn internals
After gaining experience try to check out how Backbone.js works internally and/or how node.js modules work.


## Write your own modules, libraries
When you now understood how other libraries work you can start the write your own stuff.


## Fin
Now you can call yourself an expert and beginn with transfering your ideas to code.