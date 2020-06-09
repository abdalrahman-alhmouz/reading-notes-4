# Access Control (ACL)  
  
  - in simple words :  
    Limiting what actions a user can perform on a given resource is called Access Control  


### Who might be the user types of any application and UI requirements for each ??  
 1. Admin --> manage , create , run reports ...  
 2. editor --> edite , delete , create but not mamage  
 3. guest --> read   
 4. user --> read , apply  


### How can the Backend handle these constraints ?  
  - Manage the login cycle with the front-end application  
  - Maintain the User’s database  
  - Maintain roles for each user  
  - Authenticate users (basic and bearer)  
  - Create, manage, and apply Role Based Access Controls  
  - Maintain and reference their capabilities, based on their role  
  - Restrict access to features (like routes) based on capabilities  
        + Express Middleware could be used to restrict access to routes  
        + Mongoose Middleware/Hooks could be used to restrict access to business logic  


### How can the Frontend handle these constraints ?  
  - Initiate the login process  
  - Store login tokens as cookies  
  - Manage login state, capabilities  
  - Control physical & visual access (hide/show/alter) to components based on RBAC rules  
  - Alter behaviors based on RBAC rules  


## Role-Based Access Control (RBAC)
   - is a method of restricting network access based on the roles of individual users within an enterprise  
   - access to computer resources can be limited to specific tasks, such as the ability to view, create or modify files.  
  

#### RBAC Benefits  
 -  security is more easily maintained by limiting unnecessary access  to sensitive information based on each user's established role within the organization  
 - Reducing administrative work and IT support  
 - policy 
 - revisiting least privilege 
 - each user should be able to activate the desired role 
