<h1 align="center">
🌐 the Bier Market
</h1>
<p align="center">
MongoDB, Expressjs, React/Redux, Nodejs
</p>

<p align="center">
   <a href="https://thebiermarket.herokuapp.com/">
      <img src="https://s3.amazonaws.com/hackdesign/tools/app_images/000/000/037/icon_small/heroku-logo-6e6c2ed8be2ad02ac96455d53e4e7e43.png?1385326105" />
   </a>
   https://thebiermarket.herokuapp.com/
  
   
</p>

> the Bier Market is a fullstack implementation in MongoDB, Expressjs, React/Redux, Nodejs.

## clone or download
```terminal
$ git clone https://github.com/dustinwalkup/biermarket.git
$ npm i
```

## project structure
```terminal
.env (to create .env, check [prepare your secret session])
package.json
backend/
   server.js  
frontend/
   package.json
...
```

# Usage (run fullstack app on your machine)

## Prerequirements
- [MongoDB](https://gist.github.com/nrollr/9f523ae17ecdbb50311980503409aeb3)
- [Node](https://nodejs.org/en/download/) ^10.0.0
- [npm](https://nodejs.org/en/download/package-manager/)

notice, you need client and server runs concurrently in different terminal session, in order to make them talk to each other

## Client-side usage(PORT: 3000)
```terminal
$ cd frontend   // go to frontend folder
$ npm i       // npm install pacakges
$ npm run dev // run it locally
// deployment for client app
$ npm run build // this will compile the react code using webpack and generate a folder called docs in the root level
$ npm run start // this will run the files in docs, this behavior is exactly the same how gh-pages will run your static site
```

## Server-side usage(PORT: 8000)

### Prepare your secret

run the script at the first level:

(You need to add a JWT_SECRET in .env to connect to MongoDB)

```terminal
// in the root level
$ echo "JWT_SECRET=YOUR_JWT_SECRET" >> ./.env
```

### Start

```terminal
$ cd server   // go to server folder
$ npm i       // npm install pacakges
$ npm run dev // run it locally
$ npm run build // this will build the server code to es5 js codes and generate a dist file
```

# Dependencies(tech-stacks)
Client-side | Server-side
--- | ---
axios: ^0.21.1 | bcrypt-nodejs: ^2.4.3
react: ^17.0.2 | dotenv: ^8.2.0
react-dom: ^17.0.2 | express: ^4.17.1
react-bootstrap: ^1.5.2 | express-async-handler: ^1.1.4
react-router-boostrap: ^0.25.0 | colors: ^1.4.0
react-helmet: ^6.1.0 | jsonwebtoken: ^8.5.1
react-redux: ^7.2.3| jwt-simple: ^0.5.1
react-router-dom: ^5.2.2 | mongoose: ^5.12.3
react-scripts: ^4.0.3 | multer: ^1.4.2
redux: ^4.0.5 | morgan: ^1.10.0
redux-thunk: ^2.3.0 


## Standard

[![JavaScript Style Guide](https://cdn.rawgit.com/standard/standard/master/badge.svg)](https://github.com/standard/standard)

## BUGs or comments

Email Me: dustinwalkup@gmail.com

## Author
Dustin Walkup

### License
[MIT] 



