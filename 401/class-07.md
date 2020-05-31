# Express
  - Express is a  is a minimal and flexible Node.js web application framework that provides a robust set of features for web and mobile applications  
  -  Express.js basically helps us manage everything, from routes, to handling requests and views.  


## Express Routing  

   - Routing refers to determining how an application responds to a client request to a particular endpoint, which is a URI (or path) and a specific HTTP request method (GET, POST, and so on).

   - The Request Object  
     1. /:parameters
     2. Query Strings  
    
   - The Response Object  
      - it sends the data from the server to the browser  
      - Has methods like send() and status() that Express uses to format the output to the browser properly  


## Express Middleware 
   Number of functions that are invoked by the Express.js routing layer befor the final request handler is made  

   - Each function receives request, response and next as parameters  

   #### Types of middleware :
   1. Application Middleware
        - Error Handling
        - Bringing in other routes
        - Applies Defaults
        - JSON, Body and Form Parsing
        - Runs on every request
    
    2. Route Middleware
        - Dealing with specific things for a route
        - Generally, things many routes would participate in  


   #### How it works ?
   ![http request](./img/HTTP_Request.png)  


   ## Test Pyramid
     - **Units**: Server Internal Functions

     - **Integration**: How it connects to other services

     - **Acceptance** if the sever dependence on some other test
     