# Event Driven Programming  
   -  is a useful way to create interactive websites  
   - after the webpage has loaded the JavaScript program continues to run waiting for an event  
   - If you connect this event to a JavaScript function then the function will run when the event occurs  

 ![event driven](./img/event_loop.jpg) 


## what are the  concepts that Event-Driven Programming makes use of ?  

  1. An Event Handler is a callback function that will be called when an event is triggered.  
  2. A Main Loop listens for event triggers and calls the associated event handler for that event.  

## EventEmitter  
 The EventEmitter class is defined and exposed by the events module:  
   `const EventEmitter = require('events');`  
 All EventEmitters emit the event 'newListener' when new listeners are added and 'removeListener' when existing listeners are removed.  
 

 