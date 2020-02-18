# Links 
 - We know that every website has more than one page so if we want to move from one page to another we have to use link, also we can link the page to a specific part of the same page or to other website 

    1. link to other website

        ```
         <a href = "www.google.com "> google </a>
        
        ```
    2. link to part of the same page 

        ```
         <a href="#header2">go to header 2</a>
         <h2 id="header2"> ... </h2>

        ```
    3. link to other webpage on the same website

        ```
         <a href="contact.html">Contact</a>

        ```
    we call this a relative url 
    

    4. link to sent an email to anyone's email address

        ```
            <a href="mailto : name@email.com"> Email name </a>

        ```

 - if we want to open the link in a new window we use (target-"blank") for example :

   ```
     <a href="http://www.ltuc.com" target="_blank"> ltuc </a>

   ```


# Layout 
  - we know that the browser display pages using normal flow unless we change it using :
     + specify relative
     + absolute
     + fixed positioning
  - we can also use float to place elements side by side 
  - Thers is three ways that we can use to control our webpage display resolution to fit any screen no mater of the size 
     + fixed width Layouts
     + Liquid Layouts
     + Layout grids

  - Some times we need to use more than one style sheet on our webpages so :
     + either we import it ``` @import url("style.css");  ```
     + or we link it ```  <link rel="stylesheet" type="text/css"    href="css/site.css" />  ```

# Functions 
  - we need functions when we have some code and we want to rpeate it more than one time in a several situation , to declare a function :
    ``` 
     function name(){
         the code ;
         retrne some value ; 
     }

    ```

# pair programming
   this programming way is like a collaborative envioronment for the programmers to share a single workstation to interactively tackle a coding task together
  