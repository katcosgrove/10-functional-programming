10-functional-programming - Code 301, Day 10

Author: Kat Cosgrove

Version: 1.10.0

Overview

This app is hosted on a local server. The articles are being stored and handled by two tables in a postgreSQL database.

Using AJAX, we now retrieve our data from a remote source, rather than loading it in through a JS script. Further, in order to make the page load faster, we store this data after the initial retrieval into localStorage, thus avoiding additional server queries.

The page still utilizes jQuery to dynamically render the content based on user input by making modifications to the provided starter code.

We utilize the Handlebars.js library to create cleaner templates and populate our blog.

Getting Started
====

Clone the repo and initialize your node package manager. Install dependencies, then launch your SQL database. Follow the TODO items within the starter code, making sure to pay attention to REVIEW items.

Architecture
====

This page utilizes AJAX and SQL to make remote server calls for content, handlebars.JS to template the content, and we used the jQuery library to create an article template to populate our app with data sourced from our data file. Articles are organized within two postgreSQL tables.

We approached this design with a mobile first mindset. Then we used media queries to adjust the design for viewports wider than 640px. We are using HTML and CSS, as well as normalize.css and the icomoon hamburger menu icon.

Change Log
====

11/5/17 9:00AM Start working. Stare, glassy-eyed, at the TODOs.

11/5/17 10:00AM Turn on 30 Rock. Liz Lemon's disasters sooth you.

11/6/17 11:00AM Remove your IIFEs, because you're doing SOMETHING wrong and figure it's best to eliminate things you aren't 100% sure about.

11/6/17 12:00PM Get a mug of hot chocolate. Realize you have a bottle of creme de menthe. It's Sunday, why not.

11/6/17 12:30PM Get the template, author count, and word count working.

11/6/17 1:00PM Put your IIFEs back in place. Break everything.

11/6/17 2:00PM Give up for the day, unsure of what's still broken and what's fixed.

11/7/17 10:00AM Realize you made a real dumb mistake, and didn't actually attach the module to the Article or articleView correctly. You also didn't call the app at the end of the IFFE.

11/7/17 11:00AM Things magically work.

11/7/17 11:30AM Refactor forEach into .map, get the author stats working. High-five yourself.

Credits and Collaborations
====

Code Fellows - https://www.codefellows.org/
normalize.css - https://necolas.github.io/normalize.css/
icomoon - https://icomoon.io/
jQuery - https://jquery.com/
Handlebars.js - http://handlebarsjs.com/
node.js - https://nodejs.org/en/
