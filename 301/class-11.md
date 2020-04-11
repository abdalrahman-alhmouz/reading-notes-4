# EJS  
  is a simple templating language that let us generate HTML markup with plain JavaScript  

- to install it we need this command ` npm install ejs `   

- the tags that we use it for EJS :   

 1. `<%` 'Scriptlet' tag, for control-flow, no output    
 2. `<%_` ‘Whitespace Slurping’ Scriptlet tag, strips all whitespace before it    
 3. `<%=` Outputs the value into the template (HTML escaped)  
 4. `<%-` Outputs the unescaped value into the template  
 5. `<%#` Comment tag, no execution, no output  
 6. `<%%` Outputs a literal '<%'  
 7. `%>` Plain ending tag    
 8. `-%>` Trim-mode ('newline slurp') tag, trims following newline  
9. `_%>` ‘Whitespace Slurping’ ending tag, removes all whitespace after it  

# EJS let's us =>
 spin up quick applications when we don't need anything too complex.  
  By using partials and having the ability to easily pass variables to our views, we can build some great applications quickly.