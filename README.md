# basic-auth

building express server with user authentication, hash encryption and db storage using PostgreSQL

## Author: Rami zaitoun

**Version**: 1.0.0


### <center> links and resources </center>


## PR : [Github pull request](https://github.com/MasteRminD6666/basic-auth/pull/1) </center>
#### 
-----------

## <center> [Herokuo-signup](https://rami-basic-auth.herokuapp.com/signup) </center>
## <center> Json {
    "username": "mastermind",
    "password": "password"
}

## <center> [Herokuo-signin](https://rami-basic-auth.herokuapp.com/signin) </center>
## <center> Json {
    "username": "mastermind",
    "password": "password"
}



## <center> UML DIAGRAM </center>

![web request response cycle diagram](https://raw.githubusercontent.com/MasteRminD6666/basic-auth/main/web-rami.png)

## Overview

building an express server with node.js. Writing our own tests with supertest and jest. Two POST routes (/signup and /signin). Modularize the code.

## Setup

git clone repo from github link:
https://github.com/MasteRminD6666/basic-auth
.env requirements
PORT - Port Number


npm install
(to install dependencies: express, dotenv, supertest, jest, base-64, bcrypt, cors)

Running the app
npm start
Endpoint: /signup to create a new user profile (username and password)
Endpoint: /signin to check credentials against stored hashed values

## Architecture

node.js based server that uses express library and dotenv package



