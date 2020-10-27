## Reading: Class 31

### React Custom Hooks
A custom Hook is a JavaScript function whose name starts with ”use” and that may call other Hooks. Custom Hooks are a mechanism to reuse stateful logic (such as setting up a subscription and remembering the current value), but every time you use a custom Hook, all state and effects inside of it are fully isolated. 
### Hook Rules
Only Call Hooks at the Top Level
Don’t call Hooks inside loops, conditions, or nested functions. Instead, always use Hooks at the top level of your React function. By following this rule, you ensure that Hooks are called in the same order each time a component renders. That’s what allows React to correctly preserve the state of Hooks between multiple useState and useEffect calls.
Only Call Hooks from React Functions
Don’t call Hooks from regular JavaScript functions. Instead, you can:
Call Hooks from React function components.
Call Hooks from custom Hooks (we’ll learn about them on the next page).
By following this rule, you ensure that all stateful logic in a component is clearly visible from its source code.
### Custom Hooks - All You Need To Know
Five Important Rules for Hooks
Never call Hooks from inside a loop, condition or nested function
Hooks should sit at the top-level of your component
Only call Hooks from React functional components
Never call a Hook from a regular function
Hooks can call other Hooks
### 10 Essential React Hooks
1. useArray hook (react-hanger)
2. react-use-form-state hook (react-use-form-state)
3. react-fetch-hook (react-fetch-hook)
4. useMedia hook (use-media)
5. react-useportal hook (react-useportal)
6. react-firebase-hooks (react-firebase-hooks)
7. use-onClickOutside hook (use-onclickoutside)
8. useIntersectionObserver hook (react-use-intersection-observer)
9. use-location hook (react-use)
10. use-redux hook (use-redux)
