***READING 4A***
**MDN URLSearchParams built-in class 
Search params control how and what we search for in a url. It seems like the search params live in their own sort of object, with properties that can be added or deleted etc...  It won't parse a full url but it will filter a leading ?. 

**toString() returns query string
toString is a method we can pass on urlsearchparams to return a string suitable for a url.

**Built-in Location Object
The syntax on this one is intimidating me. We've used it because some interfaces naturally have a location, such as window and document.

**Hash change event
Is an event that fires when the hashtag section of a url is changed. Not much else here but it is a good triggering condition to know about.

***READING 4B***
**RegExr
I'll be coming back for this cheatsheet a lot I think. Not sure what else I'm supposed to do here.

**Regex Tutorial
Regular Expressions can be used to extract information from any text. It applies to many programming languages. Regex is a lot to take in. There are many operators.

**Regex 101
This looks like a fun tool to play with.

***READING 4C***
**On Callbacks and Promises
The basic idea is to run multiple lines of code simultaneously. Creating multiple threads. The browser gives JS the APIs to perform async tasks. Callbacks are very useful but also add an extra layer of nesting so be careful. Promises help get around these issues. It appears that promises are often tied to if statements.

**MDN on Asynchronous
Synchronous JS is good but has some problems. But things can get blocked which makes the app less responsive. There's some overlap about callbacks and promises.

**Promises in 20 Minutes
The land before Promises.

**Google Developer on Promises
Promises simplify deferred and asynchronous computations. A promise represents an operation that hasn't completed yet. They are like event listeners but can only succeed or fail once. A promise can be fulfilled, rejected, pending, or settled.

**MDN using fetch
This has similar infor to the following article, plus some more technical information about previous alternatives like jQuery.

**Fetching data
Fetch API is one of the best ways to get data, it makes a request and returns a promise. The promise resolves when the remote server responds with headers, then the app needs to call a response method to it to make it readable.