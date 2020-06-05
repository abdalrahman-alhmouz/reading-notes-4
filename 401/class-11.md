# Authentication  

## User Models
  - Are the models that have sensitive data that should never be sent to client applications.  


## Cryptography   

  is a method of protecting information and communications through the use of codes, so that only those for whom the information is intended can read and process it.  


## Hash Algorithms  

  - takes a piece of data and produces a hash that is deliberately difficult to reverse. If identical data is passed into the algorithm the same hash will always be produced  
  - Hash algorithms are often used for checking the integrity of data.  

  - The two most common hashing algorithms :  
     1. Message Digest 5 (MD5)  
     2. Secure Hashing Algorithm (SHA)  

  
## Cypher Algorithms  

   -  takes a piece of data and a key and produces encrypted data. Later the encrypted data can be reversed into the original data by decrypting it using the same key.  

   - The 3 main types of cryptographic algorithms:  
     1. secret key  
     2. public key  
     3. hash functions  

    
## Basic Authorization  

   - is a common method used to send a username and password in an HTTP request.  
   - a request contains a header field in the form of Authorization: Basic <credentials> , where credentials is the Base64 encoding of ID and password joined by a single colon : .
