 WIP attempt to make a file that can be consumed as both JavaScript and HTML.
 
Consume html-and-js.html:

- as a HTML file, by opening it in a browser
- as a JS file, by running it:
  - via node: `node html-and-js.html`
  - by requiring it from other JS files:  `node consume_as_js.js`

# Goals
- Should be readable by other JavaScript files as a standard JS file, including exports
- Should open as a webpage if you double-click on it, including:
  - external JS links
  - inline scripts that are invisible if opened as a JS file

# Issues

- JS comment-out (`//`) shows at the top  of the page when consumed as HTML
