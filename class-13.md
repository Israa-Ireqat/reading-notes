# Local Storage
### Before HTML, application data had to be stored in cookies, included in every server request.(Local Shared Objects).
### Web storage is per origin (per domain and protocol). All pages, from one origin, can store and access the same data.

## Web Storage Objects:
* window.localStorage - stores data with no expiration date
* window.sessionStorage - stores data for one session (data is lost when the browser tab is closed)


       
       interface Storage {
       getter any getItem(in DOMString key);
       setter creator void setItem(in DOMString key, in any data);
       };

