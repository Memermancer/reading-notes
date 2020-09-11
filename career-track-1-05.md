***Web Scraping with Javascript and Node.js
Javascript does not manipulate a computer or its resources directly. To make this work Ryan Dahl took google chrome's JS engine and made a C++ program with it called Node. So now JS can be run on servers as well as clients. It differs from a lot of languages in that it is single threaded. After this introduction the article breaks down a few http clients, including Axios, Request, and Superagent. Next the article mentions regular expressions, which it describes as being difficult. Cheerio looks pretty cool, even though I don't have experience with JQuery. JSDOM gives us a way to access the DOM in Node, which is normally not possible. Puppeteer and Nightmare are both high level browser automation libraries.

***MDN - querySelector
querySelector returns the first element within the document that matches one or more selectors. Remember to escape special characters with \.

***MDN - querySelectorAll
querySelectorAll is similar to querySelector but instead of returning the first element it returns a nodelist representing all the elements that match the criteria in the selectors argument.