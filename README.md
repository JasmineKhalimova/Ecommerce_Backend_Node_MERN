# Book store Ecommerce_App_MERN_Stack
Building an eCommerce app using MongoDB Express.js React.js and Node.js MERN stack

This is the backend of the application Express and Node.js using Mongo Atlas

Install required packages

- pakage.json file:
    npm init -y

- express:framework for Node.js, dotenv: for environmental variables, nodemon: to run server continuously: 
    npm i express doten nodemon
    
- body parser and morgan: useful for seding data through routes: 
    npm i body-parser morgan 

- Cookie parser: to save user credentials in the cookie: 
    npm i cookie-parser

- express-validator: v 5.3.1 required otherwise will recieve error: "TypeError: expressValidator is not a function": 
    npm i express-validator
After installing the express-validator then go to your package.json and update it to use version to use 5.3.1 like so -> "express-validator": "^5.3.1",

- json web token: for user signin:  
    npm i express-jwt jsonwebtoken

- formidable and lodash: to upload and send files and images:
    npm i formidable lodash

- cors: for providing a Connect/Express middleware that can be used to enable CORS with various options.
    npm install cors
    
- Install Braintree for the payment systems
    npm i braintree
    
- install @sendgrid/mail for mail testing
    npm i @sendgrid/mail

*Note Node executes whatever is in app.js to execute the app: node app.json

To run the server continues nodemon has been intalled and set up in package.json new comand to start the server: npm start

Using MonngoDB Atlas

DB required package instialtions to connect DB

mongoose: npm i mongoose

User types:

0 = General type user 

1 = Admin type user

Commit messages:
    press "i"
    write your merge message
    press "esc"
    write ":wq"
    then press enter
    
 Git error:
 allow-unrelated-histories switch. After a git pull or git merge command, add the following tag:

git pull origin master --allow-unrelated-histories
