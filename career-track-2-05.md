## Reading: Class 30

### Hooks API
Hooks were introduced in React 16.8, they let you use state and other React features without writing a class. They are backwards compatible. UseState hooks are called inside function components so it can use state. It is similar to setState but doesn't merge old and new states. Hooks in general are functions that use react state directly. UseEffect hook is for performing side effects. Does similar thing to componentDidMount and family. Hooks are JavaScript functions, but they impose two additional rules:
Only call Hooks at the top level. Don’t call Hooks inside loops, conditions, or nested functions.
Only call Hooks from React function components. Don’t call Hooks from regular JavaScript functions. (There is just one other valid place to call Hooks — your own custom Hooks. We’ll learn about them in a moment.)
### State Hook
Set state with the useState hook. The argument is the initial state, which does not need to be an object. It returns the current state and a function that updates it.
### Effects Hook
Effects hook can be good for manually changing DOM elements in React components and other side effects, such as network requests. useEffect runs after every render. It also does not block the screen from being rendered, unlike componentDidMount. Cleanup is something we haven't really messed with but useEffect can work here too.
### Hooks API Reference 
Favorited!
