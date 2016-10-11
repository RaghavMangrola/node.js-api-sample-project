# A node.js API that will

* Handle CRUD for an item (users)
* Have a standard URL (http://example.com/api/users and http://example.com/api/users/:user_id)
* Use the proper HTTP verbs to make it RESTful (GET, POST, PUT, and DELETE)
* Return JSON data
* Log all requests to the console


## Dependencies

* express
  * Node Framework
* morgan
  * Allows us to log all requests to the console so we can see exactly what is going on
* mongoose
  * The ODM we will use to communicate with our MongoDB database
* body-parser
  * Lets us pull POST content from our HTTP request so that we can do things like create a user
* bcrypt-nodejs
  * Allows us to hash our passwords since it is never safe to store passwords plaintext in our databses
