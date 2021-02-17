# ***HTML Links, JS Functions, and Intro to CSS Layout***
---
## Links
**Links allow the user to move from one page to another.
The elememnt for creating links is `<a>` and the page to be linked is specified by `href` attribute.**
`<a href="http://www.google.com">IMDB</a>`
* **Linking to other sites**
Use the full web address (Absolute URL)
* **Linking to other pages in the website**
Use the (Relative URL)
   * Same folder: `href="page.html"`
   * Child folder: `href="folder/page.html"`
   * Grand child folder: `href="collection/folder/page.html"`
   * Parent folder: `href="../index.html"`
   * Grand parent folder: `href="../../index.html"`
* **Email links `mailto:`**
* **Opening links in new window `target`**
`<a href="http://www.google.com"target="_blank">`
* **Linking to a specific part in the same page**
Using the `id` attribute.`#`
* **Linking to a specific part from another page**
Using the `id` attribute after the page link.`<a href="http://www.google.com/#bottom">`
