# React Testing  
  There are a few ways to test React components. Broadly, they divide into two categories:  
   1. Rendering component trees  
     - in a simplified test environment and asserting on their output.  
   2. Running a complete app  
     - in a realistic browser environment (also known as “end-to-end” tests).  


## React testing approaches  
  - Snapshots  
  - Render Testing  
  - Shallow Testing  
  - Mounting 


# React Deployment  
  - It uses a node service to create a live website that refreshes as you write code.   
  - React, is an index.html file that uses Javascript to render components in the browser  
  - The node server is only there to aid in your development.  

## Deploying to AWS (s3)  
 - Create a new Bucket
 - Objects
 - Set up to serve websites  

## Deploying to AWS Amplify  
 - Create a new Amplify Workflow  
 - Point the workflow at your GitHub repository (master branch)  
 - Merge your code to master on GitHub  
 - Amplify will monitor your repository for changes, pull, build, and deploy your React app automatically  


## Deploying to Netlify  
 - Create a netlify.com account  
 - Create a new application  
 - Point the application at your GitHub repository (master branch)  
 - Merge your code to master on GitHub  

## Deploying to an “old school” host  
 - Create your account  
 - Open an FTP connection to your hosting company with a tool like Transmit or FileZilla  
 - Navigate to the web root folder  
 - Upload the contents of your react application’s build folder  