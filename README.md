# Node.Js API Authentication with JWT
This is an API that is going to handle Authentication for any application.
I used Authntentication method called Json Web Token (JWT) as a middleware for protected routes, mongoDB to store users
and bcrypt.js to hash passwords.

### Usage
1. `npm install`.
2. `npm start`.
3. Open Postman and make a POST request to register a new user `http://localhost:3000/api/user/register`.
4. A POST request to login a user `http://localhost:3000/api/user/login`.

### MongoDB
Open .env file and add your MongoDB URI, local or atlas



