## Reading: Class 32

### Context API
Context allows us to manage universal state, we can pass data down the component tree without the use of props! Use context when some piece of state needs to be accessed globally, across the whole application. Sometimes component composition is easier but I don't like the example very well. The defaultValue argument is only used when a component does not have a matching Provider above it in the tree. This can be helpful for testing components in isolation without wrapping them. Every Context object comes with a Provider React component that allows consuming components to subscribe to context changes. The Provider component accepts a value prop to be passed to consuming components that are descendants of this Provider. 

const MyContext = React.createContext(defaultValue);
