***Clean Code
Some tips from chapter 2.
-The name of a variable should tell you why it exists, what it does, and how it is used (this is from class too!)
-if a name requires a comment, that's no good
-Avoid disinformation, including words with multiple meanings or specific meanings to programmers
-Pronounceable and Searchable names help in discussion and when you need to find it later.
-Classes should be nouns, Methods should be verbs
-Don't be cute or punny
-One word per concept

***Array Methods
1)forEach: used this one to some effect a few times
2)includes(): included this once or twice in projects, just the right tool sometimes
3)filter(): very powerful method, and often part of code challenges
4)map(): I use map all the time and it is one of my favorite array methods
5)reduce(): this one is tricky and I haven't wrapped my head around it yet
6)some(): this article is the first I have heard of this method...interesting
7)every(): some()'s pickier sibling 
8)sort(): I've tried to make this work before and had some difficulty
9)Array.from(): making array like things into arrays? Interesting
10)Array.of(): new to me and pretty cool way to make an array

***Array Methods Cheat Sheet
Very beautiful site first of all. Great flow chart and array method breakdown. Saving this resource.

***Class Syntax
Classes are great for creating many objects in the same mold. Classes in JS are a kind of function, which makes a lot of sense given our experience in react. Classes can be called in different ways than a 'manual' function which makes it more than syntactic sugar. I don't know much about the 'constructor' term. I'll have to study more.

***MDN-Classes
Classes are a template for creating objects. They are a type of special function that creates objects. Class declarations are one way to define a class. Class declarations do not hoist. Class expressions are another way to define classes. They can be unnamed. Great! Here is some stuff about constructors for me to study. Some of the following stuff is pretty heavy and I hope we can go over it in class. Could be very helpful in game design though, which is my long term goal.

***MVC
MVC = Model View COntroller, an architectural pattern that splits apps into 3 primary pieces of logic: the model, the view, and the controller. The model represents all the data related logic that the user uses. The view corresponds to the UI logic of the app, and the controller is the interface between the model and view components. ASP.NET has some cool features that the article plugs, such as enhanced testing.

***MVC Architecture Tutorial
MVC is a predictable software design pattern. We can use it in JS, but also in other languages like Python. The main purpose of the MVC model is to separate the business logic from the presentation layer. MVC has many benefits including: its popularity in web apps, distributed responsibility between the client and the server, provides a helpful design pattern for development, and defines what concerns a piece of code should have.

***MVC Explained in 4 Minutes
Patterns allow developers to understand a large application into distinct sections. This enables large teams to work on the same project, and divide work and responsibilities appropriately. Controller handles the request flow, saving, user info, authentication, etc.. While the model actually provides the data needed. The model has the data logic and directly interacts with the database. The controller can take the response from the model and sends that data to the view. The view only is concerned with dynamically rendering the data. It sends that back to the controller which can handle the final display to the user. The view and the model never directly interact with each other.
