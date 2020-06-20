# html2json
### Description
All websites serve pages from the server as an html file. Although this cannot be changed for initial fetch/open requests, this can be altered for lazy/on-demand html files. The server can be made to serve the html content in a json format and then the client can convert the json to html and use it in the DOM.
### Advantages
* Serving JSON is much faster than serving an html file.
* Full utilization can be made when manipulating the JSON in server which cannot be done for jsp.
* JSON is light weight when compared to HTML.
### Disadvantages
* Converting the JSON to HTML in client is an unwanted process.
