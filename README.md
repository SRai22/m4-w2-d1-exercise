# Authentication 

This example demonstrates how to use [Express](http://expressjs.com/) 4.x and
[Passport](http://passportjs.org/) to authenticate users using a username and
password with [form-based authentication](https://en.wikipedia.org/wiki/HTTP%2BHTML_form-based_authentication).


## Instructions

To install this app on your computer, clone the repository and install
dependencies.

```bash
$ git clone https://github.com/SRai22/m4-w2-d1-exercise.git
$ cd m4-w2-d1-exercise
$ npm install
```

Start the server.

```bash
$ node server.js
```

Open a web browser and navigate to [http://localhost:3000/](http://127.0.0.1:3000/)
to see the example in action.  Log in using username `westcliff` and password `secret`.

## Features

- Express 4.x server
- Passport.js authentication
- Local strategy for username/password login
- EJS templating engine
- Session-based authentication
- Login and logout functionality

## Dependencies

- express
- passport
- passport-local
- ejs
- body-parser
- connect-ensure-login
- express-session
- morgan

