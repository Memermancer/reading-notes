***Why you should use bcrypt
Passwords are obviously important to cybersecurity, and most are simply not good enough. The bcrypt hashing function, designed in 1999, solves many of the common problems with other password solutions and is much less vulnerable overall. Key factors are used to increase resistance to hacking.

***Understanding bcrypt
Bcrypt hashes every password with salt and its hashing scales with computational power. Brute force attacks prey on fast hashing, so interestingly the slower solution is superior here. It works through slow key changes and a variable number of iterations to increase workload.

***Where to store JWT
Where do we store tokens? Securing transactions between APIs cannot be read by malicious javascript of cross site scripting. Auth is needed when accessing a page, and api route, or when your app makes an api call on behalf of a user. Without an api call, only a token should be necessary, and it shouldn't need to be stored. Using something like auth0 is recommended for single page apps. Browser memory is generally the best place to store tokens. 