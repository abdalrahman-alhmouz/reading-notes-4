# Object 
  we all know that the variables on java script are containers for some data values , so first you should Know is te objects are also a variables but it can contain many values for example :
     
 + This normal variable ``` var laptop = "Dell"; ```
 + This is an object  ``` var laptop = { type : "Dell" , color : "black" , model : ""2019"} ```
 
 As we notice that the values for the object written as pairs (name and value separated by a colon) ``` name:value ```

### How to access the object ?
  There is two ways :
  1. objectName.propertyName ``` laptop.type; ```
  2. objectName["propertyName"] ``` laptop["type"] ``` 

### objects also have methods , so what is the method ?
  it's some kind of action that can be performed on object and it's a function stored as a property 

    ```
        var person = {
        firstName: "israa",
        lastName : "othman",
        id       : 1234,
        fullName : function() {
        return this.firstName + " " + this.lastName;
        }
        }; 

    ```

# Document Object Model 
  it's the way that the browser represents the page using it and it have four types :
  1. Document nodes 
  2. Element nodes 
  3. Attribute nodes 
  4. Text nodes 

  And we can select element nodes by :
  - Their ID / Class
  And the attributes by :
  - tag name 
  - css selectors syntax 


  
   
