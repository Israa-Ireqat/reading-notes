# **EJS Partials **
EJS partials can work without the express-ejs-layouts module. EJS partials apply in cases like creating objects like header, footer, div. NB: For a web page to contain the partial, it must be connected to each partial via a line of code, unlike layouts which apply everywhere.
### home page:
![](https://miro.medium.com/max/2538/0*VngdKfkNNx5f2un0.png)
### the post page : 
![](https://miro.medium.com/max/700/0*oUmdAzjcwkQZb_AR.png)
### same navigational bar and footer in both pages, so all navigational bars will be in one `ejs`file and all footers will be in one `ejs`file.
Including a partial in EJS is quite straightforward. You use `<%- include( PARTIAL_FILE ) %>` where the partial file is relative to the template you use it in.

