# lab 07: bearer-auth

### Author: Megan Seibert-Hughes

### Problem Domain  

Bearer-auth is a an API server that consists of routes for sign-in, sign up, and a users route. It purposely contained bugs that needed to be debugged.

### Links and Resources


### Setup

#### `.env` requirements (where applicable)

- `PORT` - 3001
- `DATABASE_URL` - postgres://localhost:5432/\<database-name\>?sslmode=disable

#### How to initialize/run your application (where applicable)

- `npm start` 

#### Features / Routes

- GET : `/` - return "We're live!!!"
- POST : `/signup` - provide username and password in the body, and receive encryptede jwt token as a response
- POST : `/signin` - provide username and password as basic auth
- GET : `/users` - provide encrypted jwt token and receive list of user records as a response

#### Tests

- test suite was provided as starter code
- run tests with `npm test`

#### UML

![UML]()

### Attributions
