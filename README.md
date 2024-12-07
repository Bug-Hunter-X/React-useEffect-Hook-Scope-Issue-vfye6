# React useEffect Hook Scope Issue
This example demonstrates a common error in React's `useEffect` hook where a variable is accessed from outside its intended scope.
The `setCount` function, declared within the `MyComponent` functional component, is not accessible within the `useEffect` hook unless explicitly passed. This leads to a runtime error when the component mounts.