# Context API  
  - Context provides a way to pass data through the component tree without having to pass props down manually at every level.  

## When to Use Context  
  - Context is designed to share data that can be considered “global” for a tree of React components, such as the current authenticated user, theme, or preferred language.  

## Before You Use Context  
  Context is primarily used when some data needs to be accessible by many components at different nesting levels.   Apply it sparingly because it makes component reuse more difficult.  

## Attach to context  
 1. Wrap your component with, and use a function to “get” the context object itself  
 2. Statically declare a connection to the context provider and then use.  

 