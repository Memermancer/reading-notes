**Node.js
Node.js has a few definitions. The project calls it a 'runtime' built on javascript. Stack overflow calls it 'an event-based, non-blocking, asynchronous I/O runtime'. It relies on the V8 Javascript engine built into chromium based browsers. The creator of Node, Ryan Dahl, took the engine and added many features, making it its own program that can excute javascript. 
A version manager can help keep node up to date.
Node supports the most modern javascript features.
Node is bundled with a package handler called npm. This can be used to install packages for even more features! We might take advantage of npm's ability to do a local installation.
Npm, using the modules directory, can also help anyone who clones your project to easily download any dependancies that the project requires.
The use of both of node and npm is for installing and running build tools that make development easier, like testing! It also lets us run javascript on a server, sounds like something we will soon use.
The execution model section is tough to follow, but what I get out of it is that node is single threaded but has asynchronous behaviors to efficeiently manage a large number of operations.
Node is extra special when used for apps with a lot of collaboration.