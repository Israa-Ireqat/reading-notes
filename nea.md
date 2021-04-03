# Node.js
![](https://jelvix.com/wp-content/uploads/2019/11/Node.js_.jpg)
### Node.js is an open-source, cross-platform, back-end, JavaScript runtime environment that executes JavaScript code outside a web browser.Node.js lets developers use JavaScript to write command line tools and for server-side scripting—running scripts server-side to produce dynamic web page content before the page is sent to the user's web browser.
---
### Node Is Built on Google Chrome’s V8 JavaScript Engine.
### You can check that Node is installed on your system by opening a terminal and typing `node -v`
-----
## JavaScript Package Manager:
### Installing a Package Globally
* `npm install -g jshint`
* `jshint index.js`
* `npm init -y`
* `npm install lodash --save`
*       const _ = require('lodash');

       const arr = [0, 1, false, 2, '', 3];
      console.log(_.compact(arr));
  If you open the `package.json` file, you’ll see lodash listed under the `dependencies` field. By specifying your project’s dependencies in this way, you allow any developer anywhere to clone your project and use `npm` to install whatever packages it needs to run.    