One thing to mention is that appending
callback=?
to the end of the URL enables us to make cross-domain JSON and AJAX calls. Don’t forget this, otherwise the data will be limited to your own domain! This method uses what’s called JSONP (or JSON with padding), which basically allows a script to fetch data from another server on a different domain. To do this, we must specify the callback above when jQuery loads the data. It replaces the ? with our custom function’s name, thereby allowing us to make cross-domain calls with ease.
