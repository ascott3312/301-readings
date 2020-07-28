# REST

## SuperAgent

SuperAgent is light-weight progressive ajax API crafted for flexibility, readability, and a low learning curve after being frustrated with many of the existing request APIs. It also works with Node.js!

### GET requests
The .query() method accepts objects, which when used with the GET method will form.

### HEAD requests
You can also use the .query() method for HEAD requests. The following will produce the path /users?email=joe@smith.com.

#### POST / PUT requests
A typical JSON POST request might look a little like the following, where we set the Content-Type header field appropriately, and "write" some data, in this case just a JSON string.

#### Multipart
The Node client supports multipart/form-data via the Formidable module. When parsing multipart responses, the object res.files is also available to you. Suppose for example a request responds with the following multipart body: