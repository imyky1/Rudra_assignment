# Rudra_assignment
REST API using NodeJS with the following features  
1. Authentication (using username and password)
2. The code have create, edit, update and delete functionality for users.
3. Forget password api

# run it locally
1. Clone the repository
2. Cd to project directory
3. create a dev.js file in config folder and write the below code
  ```
    module.exports={
    DB_URL : <YOUR_DB_URL>,
    JWT_SECRET : <YOUR_JWT_SECRET>,
    SMTP_USER   : <STMP_EMAIL>,
    SMTP_KEY : <SMTP_KEY>
}
   ```
4. Replcae <YOUR_DB_URL>, <YOUR_JWT_SECRET>, <STMP_EMAIL> , <SMTP_KEY> with your credentials 
5. Run this command
```
npm init
```
```
nodemon app.js
```
6. Wait for message
 ```
   Mongo is connected
   ```
7. use Postman or Hoppscotch to test all the API's


