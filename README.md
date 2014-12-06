# Setting up a fake HTTP server using the Node packages Express and Faker

This is a starter project for serving random fake JSON data locally. It's taken from [this Egghead.io tutorial][tutorial].

## Prerequisites

You need to have [Node.js][node-download] and [Node Package Manager (npm)][npm] installed. Of course all installs can be done
manually without `npm` but I recommend `npm` because it makes life easier.

## Setup

We'll be using [express] and [faker] and [nodemon]. To install run:

```
npm install express faker nodemon
```

## Development

Create a `server.js` script as included here. How to extend this should be self-explanatory. All the details can
be found on the links to [express] and [faker].

## Deployment

To run the server just run

```
nodemon server.js
```

To check out if it's working, go to whichever address you're serving your data. For the example here you'd go to

```
http://localhost:3000/random-user
```

and you should see a random user in JSON format.


[npm]: https://www.npmjs.org/
[node-download]: http://nodejs.org/download/
[express]: http://expressjs.com/
[faker]: http://marak.com/faker.js/
[nodemon]: https://github.com/remy/nodemon
[tutorial]: https://egghead.io/lessons/angularjs-basic-server-setup-for-jwt-authentication