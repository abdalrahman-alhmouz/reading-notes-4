# Custom Hooks  
   
  - are a mechanism to reuse stateful logic (such as setting up a subscription and remembering the current value),  
   but every time you use a custom Hook,  
   all state and effects inside of it are fully isolated  
  - Extract duplicated logic from components  
  - Share common functionality  
  - Take advantage of useEffect lifecycle  
  

## Common use cases – make things DRY!  
 - Handle forms easily  
 - Pre-fetch API data  
 - Connect to services (like socket.io, Q, etc)  


## example that demonstrates proper wiring :  
 - Hooks are exported as a function, named as useXXX()
 - Hooks return data or behaviors (functions) that are required to reuse their internal functionality
 - Hooks are imported into components
 - Components can re-use the hook functionality or data/state as needed
 - Hooks do not render


## React Hooks with Async-Await  
  - We cannot use 'async' keyword with 'useEffect' callback method. It will result in race conditions.  
    - so we should fetch our data from an API then updating our 'setResult' state  
    so React.useEffect method will only run when our 'state' got change.  
    



