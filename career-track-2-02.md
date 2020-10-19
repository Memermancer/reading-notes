##Reading: React Props and State

###Understanding React `setState`
React components can have state. This is one of the advantages to react, that it allows the display to react to state changes. setState() is the only legitimate way to update state after initial setup. setState() takes an object then react reconciles it with the state object. setState acts almost like a sanitizer for state changes.

###Lists and Keys
React can turn arrays into elements! Really cool for making lists. Assign keys to elements to help react identify what items have been changed, added or removed. Keys only need to be unique among siblings. Specify keys inside the array!

###Typechecking With PropTypes
Typechecking can catch bugs in react apps. By assigning the special propTypes property you can run typechecking on a component. PropTypes exports a range of validators that can be used to make sure the data you receive is valid. In this example, we’re using PropTypes.string. When an invalid value is provided for a prop, a warning will be shown in the JavaScript console. For performance reasons, propTypes is only checked in development mode.

 ###Components and Props
 Components are similar to Javascript functions. They accept props and return react elements. They can be defined via a js function or an ES6 class. Components can refer to other components in their output, allowing as much detail as needed for the project. Extract components to increase legibility and modularity. Components cannot modify their props.

 ###Handling Events
 Syntax difference between DOM events and react events: React events are named using camelCase, rather than lowercase, with JSX you pass a function as the event handler, rather than a string. Remember to call preventDefault explicitly in react.

 ###Snapshot Testing
 Snapshot tests are a way to test the display of a ui. It renders a ui component, takes a snapshot of it, then compares it to a reference snapshot file. Test renderer from Jest can help us by not requiring us to build the whole app for each test. Use <jest --updateSnapshot> if a new snapshot is needed for testing, otherwise jest will use the first one over and over. There is also an interactive snapshot mode which can be accessed during watch mode.

 ###Introducing the react-testing-library 🐐
 Lightweight solution for testing react components. It works with actual DOM nodes istead of rendered react components, to better simulate what the software is meant to be doing. It replaces the testing library enzyme, which has many more features which can impede easy and confident testing. It will be good to dive into testing react, because I don't feel confident in this area.