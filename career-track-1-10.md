***User Modeling
In modern web design, sensitive information needs to be modeled about user. Users trust that their information will not be leaked or misused. The developer has a responsibility to keep that information secure. Using a second model for sensitive data that client applications should never access and encrypting passwords will go a long way toward securing your application.

***Cryptography
Bookmarked the GNU dictionary

***Hash Algorithms
These algorithms take a piece of data and create a hash that is difficult to reverse. Identical data always produces the same hash. They can be used to check the integrity of the data. It also allows a user to input their password on the front end but only actually have a hash stored on the back end.

***Cypher Algorithms
These take a key and a piece of data and encrypts it. The encryption can be reversed later using the key.

***Basic Auth
A common way to send a username and password in an http request. The two are joined with a : and then base64 encoded. This string is set to the authorization header. The server decodes the information. This is not encryption, use https.

***Securing Passwords
I got a 404 error

***Basic access authentication
Overview and breakdown of basic auth using base64.

***Introduction to JSON Web Tokens
A JWT is an open standard that defines a way to securely transmit information between parties as a JSON object. It is digitally signed and therefore trustworthy. Favorited.

***Authentication Cheat Sheet
Bookmarked! Looks very useful for the days to come. It is cool that we are finally approaching the level of development where we have to clean everything up and protect it.

***bcrypt
Library for hashing passwords! This will make it all possible.