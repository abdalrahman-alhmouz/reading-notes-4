# Node Ecosystem, TDD, CI/CD


## Why would you want to run JavaScript code outside of a browser?  
   before we can run the JavaScript outside the browser   
   we use to see the result of our code in the user interface   
   which is on the screen (frontend)  
   but after we start using node.js that makes our javaScript interact with the database and creating APIs  
   (this type refers to the backend)  


## What is the difference between a module and a package?  
   The module is a file(libraries) for Node.js and it doesn't require to have package.json, thus the package can contain module or more but it required to contain package.json  
   
## What does the node package manager do?  
  It is a command line tool that installs, updates or uninstalls Node.js packages in the application.
 
## Provide code snippets showing 3 different ways to export a function from a node module  
   1. Using the function name `module.exports = functionName()`  
   2. Using object if we want to export more than one function  
      `module.exports = {one:functionX , two:functionY}`  
   3. Using anonymous function `module.exports = () =>{...};`  

### Vocabulary Terms   

| Terms         | Def           | 
| ------------- |:-------------:|
| ecosystem     | a collection of software projects, which are developed and co-evolve in the same environment |
| Node.js       | is a JavaScript runtime built on Chrome's V8 JavaScript engine. As an asynchronous event-driven JavaScript runtime      |
| V8 Engine     | is Google’s open source high-performance JavaScript and WebAssembly engine, written in C++, and engine is a computer program that executes JavaScript (JS) code     |
| module        | is any file or directory in the node_modules directory that can be loaded by the Node.js require() function     |
| package       | is a file or directory that is described by a package.json file     |
| npm           | is the world's largest Software Library, A package manager is a collection of software tools that automates the process of installing, upgrading, configuring, and removing computer programs for a computer's operating system in a consistent manner      |
| server        | is a computer program or a device that provides functionality for other programs or devices, called "clients". This architecture is called the client–server model      |
| environment   | is quite literally everything installed on your machine which can affect either the development and or testing of your application      |
| interpreter   |  is a computer program that directly executes instructions written in a programming or scripting language, without requiring them previously to have been compiled into a machine language program      |
| compiler      |  is primarily used for programs that translate source code from a high-level programming language to a lower level language      |


  
