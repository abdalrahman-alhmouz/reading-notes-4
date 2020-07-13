# Redux - Asynchronous Actions  
  
## Why Do we need Redux Thunk ?
    With a plain basic Redux store, you can only do simple synchronous updates by dispatching an action.  Middleware extend the store's abilities, and let you write async logic that interacts with the store.  

## Redux Thunk Middleware  
    allows you to write action creators that return a function instead of an action.  
    The thunk can be used to delay the dispatch of an action, or to dispatch only if a certain condition is met.  
    The inner function receives the store methods dispatch and getState as parameters.  

## What’s a thunk?!  
   A thunk is a function that wraps an expression to delay its evaluation.  

## Asynchronous Redux Actions Using Redux Thunk  
  The most common use-case for Redux Thunk is for communicating asynchronously with an external API to retrieve or save data.  
  Redux Thunk makes it easy to dispatch actions that follow the lifecycle of a request to an external API.
 