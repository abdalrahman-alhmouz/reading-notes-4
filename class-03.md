# Lists 
In HTML 5 there is three types of lists :
1. orderd list **(with numbers)**

  ```
        <ol> 
            <li>  </li>
            <li>  </li>
            <li>  </li>
        </ol>

  ```
2. unorderd list **(with bullets)**

    ```
        <ul> 
            <li>  </li>
            <li>  </li>
            <li>  </li>
        </ul>

    ```
3. definition list 

    ```
        <dl> 
            <dt>  definition term </dt>
            <dd> definition </dd>
        </ol>

    ```

# Boxes 
we know that each element on html has a space around it like a box
and we can change the design of these boxses using some css styles like :
- width and hight
- border 
- margin 
- padding 
- display 


# Decisions and Loops
we already know what is the if statment and the switch statment. 
the new thing is how to rewrite an if statment as a switch    
+ for example :

```

    if(num == 0){
        print zero 
    } else if (num == 1){
        print one;
    }else {
        print nothing 
    }

```

```
 switch (num){
    case 0 :
      print zero ;
      break;
    case 1 :
      print one ;
      break; 
    default :
     print nothing ;
     break;
}

```

+ also we can use decision statments inside the loops or the loops inside the decision statments , for example :

```
    if (name === 'israa'){
    while (i < 5) { 
        print name;
        i++ ;}
    } else { 
    while ( i < 5) { 
        print nothing;
        i++; }
    }

```
  
 