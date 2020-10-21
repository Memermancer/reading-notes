##Reading: Class 28

###Architectural Styles and Architectural Patterns
In software engineering, an Architectural Pattern is a general and reusable solution to an occurring problem in a particular context. It is a recurring solution to a recurring problem. Design Patterns impact a specific section of the code base, Architectural Patterns are high-level strategies that concern large-scale components, the global properties and mechanisms of a system.

###Container and Presentation Pattern
Container components are concerned with how things work. In this role they manage state, fetch data from APIs, setup event handlers, and pass information to other components via props. Presentation components are concerned with how things look. In this role they receive props and use those props to render and style DOM.

###Container Component Details
When the Container/Presentation pattern first became popular all containers were class based components. At that time state and lifecycle methods were only available within class components. Since containers are responsible for managing state and fetching data (lifecycle methods) they were exclusively written as class components. This helped highlight the dichotomy between container components (classes) and presentational components (functions).

###Presentation Component Details
Presentation components are responsible for specifying how a section of our page looks. They create DOM and styles.

###Functional vs Class-Components in React
The most obvious one difference is the syntax. A functional component is just a plain JavaScript function which accepts props as an argument and returns a React element.
A class component requires you to extend from React.Component and create a render function which returns a React element. Because a functional component is just a plain JavaScript function, you cannot use setState() in your component. That’s the reason why they also get called functional stateless components. So everytime you see a functional component you can be sure that this particular component doesn’t have its own state.

###Conditional Rendering
Conditional rendering in React works the same way conditions work in JavaScript. Use JavaScript operators like if or the conditional operator to create elements representing the current state, and let React update the UI to match them.