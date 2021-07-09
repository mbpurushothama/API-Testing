# API-Testing

**#Project goal is to retrive the number of pets which are in sold staus from find status API from petstore
#swagger : https://petstore.swagger.io/#/pet/findPetsByStatus**

**#Getting stated **
**#Pre-requisites to install Postman**


1.	Install Node.js latest version and add the Node executable to system path
                (i)	node – v: To check the NodeJS is installed or not, if installed the version would be displayed
                (ii)	npm – v: To check the npm version
                    
2.	Download and install Postman : https://www.postman.com/downloads/  or you can have as chrome addin 
3.	Install newman to run the collection from command prompt
5.	htmlextra reporter library for Newman and this is an npm dependency - Install to generate the HTML report to view the API results 


**#How to run collection :**
download the collection named from repository main branch : Pet_Store_API.postman_collection.json
1. Imoprt collection into postman and run

**#How to run collection using command prompt:**
1. Open command prompt
2. Navigate to json file through command prompt **ex : C:user/Pet_Store_API.postman_collection.json**
3. run command : newman run Pet_Store_API.postman_collection.json

**#How to generate detailed HTML report using htmlextra library**
1. To generate HTML report run below command :
   newman run Pet_Store_API.postman_collection.json -r htmlextra
   
   Find the sample test results in html format: Pet Store API-2021-07-09-14-03-25-094-0

