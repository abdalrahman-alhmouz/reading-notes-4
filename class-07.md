# Tables 
  Basiclly table are consist of columns and rows so to create a table we need tags for each one of them for example :

  **Name**  |  **Number**
  --------- | ------------- 
   Israa    |  1234
   Ahmed    |  5678
   Raghad   |  9101

   if we want to write this table using html :

    ``` 
     <table>
       <tr>
           <th scope="col">Name</th>
           <th scope="col">Number</th>
       </tr>
       <tr>
           <td>Israa</td>
           <td>1234</td>
        </tr>
        <tr>
            <td>Ahmed</td>
            <td>5678</td>
        </tr>
        <tr>
            <td>Raghad</td>
            <td>9101</td>
        </tr>
    </table> 
     
    ```
   but if we have a longe table we should use ``` <thead> ``` and ``` <tbody> ```and ``` <tfoot> ```

# Functions, Methods, and Objects
 we learned befor how to create an object and what dose it contain (properties / methods)
 - now we need to now how to create an instances of the objeect using the constructor function 

    ```
     var objectName = new constructor function ;
     var Ahmed = new person(20 , boy);
     Ahmed.age(22);
     Ahmed.gender(boy);

    ```

 - So there is two ways to create an object :
 1. LITERAL NOTATION 
 2. OBJECT CONSTRUCTOR NOTATION 
 

# Domain Modeling 
 it is a model that we create to make a specific problem well articulated so we can verify and validate our understanding of that problem
 