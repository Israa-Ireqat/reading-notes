# Deploy Your Blog to Heroku
###  Node.js is an open source, cross-platform runtime environment, which allows you to build server-side and networking applications.
1. create a JavaScript file
         var http = require("http");

         http.createServer(function(request, response) {
         response.writeHead(200, {"Content-Type": "text/plain"});
         response.write("It's alive!");
         response.end();
         }).listen(3000);

2. Run at your terminal: `node server.js`   
3. check it in your browser.
4.      $.post('/some_requested_resource', function(data){
        console.log(data);
                 });
5. Make it worldwide: `heroku login`
6. declare some variables :

            var http = require("http");
            var fs = require("fs");
            var path = require("path");
            var mime = require("mime");
7. `npm install` 
8. create the HTTP server:

         var server = http.createServer(function(request, response) {
       var filePath = false;

        if (request.url == '/') {
        filePath = "public/index.html";
        } else {
        filePath = "public" + request.url;
        }

        var absPath = "./" + filePath;
        serverWorking(response, absPath);
        });   
9.  It's Heroku time.
  * Do:  git  acp
10. `heroku apps:rename myfirstserver`
11. `heroku open`
