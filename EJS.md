# *How To Use EJS to Template Your Node Application*
## 1. Make yor file structure.
## 2. Setup `package.json`.
## 3.  install the dependencies `npm install`.
## 4. Setup th index.html page to full width,then configure our application to use EJS and set up our routes using the `server.js file`.
     // load the things we need
    var express = require('express');
    var app = express();

    // set the view engine to ejs
    app.set('view engine', 'ejs');

    // use res.render to load up an ejs view file

    // index page
    app.get('/', function(req, res) {
    res.render('pages/index');
    });

    // about page
    app.get('/about', function(req, res) {
    res.render('pages/about');
    });

    app.listen(8080);
    console.log('8080 is the magic port');

## 5. Start Up Server `node server.js`.
## 6. Create the EJS Partials.
 * `head.ejs`
 * `header.ejs`
 * `footer.ejs`
## 7.  Add the EJS Partials to Views `<%- include('RELATIVE/PATH/TO/FILE') %>`
## 8. Pass Data to Views and Partials
## 9. Render a Single Variable in EJS
## 10. Loop Over Data in EJS
