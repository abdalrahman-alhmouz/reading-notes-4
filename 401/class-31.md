# Hooks API  
  - Hooks are a new addition in React 16.8. They let you use state and other React features without writing a class  

  - React hooks allow to easily create and manage state in a functional component   

## Rules :
 - Hooks must be named with a use prefix (i.e. useFishingPole)  
 - Only call Hooks at the top level. Don’t call Hooks inside loops, conditions, or nested functions.  
 - Only call Hooks from React function components. Don’t call Hooks from regular JavaScript functions.  

## Built In Hooks  
  `useState() `  
  Returns a stateVariable and setterFunction for you to use to manage state in a functional component  

## How does this work?  
 - by convention, we use `set` + `statevariable` (camel cased) to name this function  
 - `useState()` takes a single param, which is the initial value to assign to the state variable  
 - You can call your setter function .. i.e. `setClicks(7)` and the attribute value you call the function with is used as the new value for the state variable.  
