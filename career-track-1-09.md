***Using express routing
Routing describes how an applications endpoints respond to requests. These endpoints correspond to the http methods. You can use a callback function(handler) or middleware(with app.use()) to create a response. Multiple functions can be used with next(). Route paths define each endpoint, along with the method. They can be strings, string patterns, or regular expressions. Route params can be used to add params to the req.params object. There's a nice list of all the response methods we can use.

***Supertest
Supertest is an API to assist in testing http applications. It is built on superagent, another API. We know it, we love it. It can simulate http requests to test an applications response.

***Using express middleware
Express applications can be described as a series of middleware function calls. Middleware functions can execute code, change the req and res objects, end the req-res cycle, or call the next function in the stack. On the application level, app.use or app.METHOD are employed to execute the function. On the router level, it works the same but is bound to express.Router() instead. Error handling middleware is similar but contains 4 arguments rather than three. Express has a few built in middleware and it's functionality can be expanded through the use of third party middleware.

***Express middleware
Middleware functions are functions that have access to the req and res objects as well as the next middleware function in the app's cycle. It is important to manage which order that middleware function execute in. Some of the most common third party middleware are body-parser(for parsing the body of requests with payloads), cookie-parser(for parsing the cookie header and populating req.cookies with the resultant object), and express-session(which creates a session middleware).

***Express middleware list
Big old list of third party middleware for express! Bookmarked.

***http status codes
Bookmarked!