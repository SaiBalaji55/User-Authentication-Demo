# User-Authentication-Demo
User Authentication demo for my college project

In a new folder:

 npm init -y
 
 npm install express bcryptjs   jsonwebtoken

Run the Server
 node server.js

1. Register → POST → http://localhost:5000/register

{
  "name": "xxx",
  "email": "yyy@domain.com",
  "password": "password"
}

Login → POST → http://localhost:5000/login

{
  "email": "yyy@domain.com",
  "password": "password"
}
