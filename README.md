# MERN stack Exercise Tracker App [![Build Status](https://travis-ci.org/rfdickerson/mern-example.svg?branch=master)](https://travis-ci.org/rfdickerson/mern-example)

The MERN stack starter demonstrates a working application that uses a React frontend, with a backend build with ExpressJS and MongoDB. It shows how the client can make client HTTP requests and maintain persistant sessions.

## Configuration (Optional)

By default, the server will expect to connect to a MongoDB instance running. However, you can customize the environment to use different values for the MongoDB host. To do that, you can create a `.env` file for specifying credential information for MongoDB.

Create a new file called `.env`, with the following YAML:

```yaml
ATLAS_URI=mongodb+srv://<username>:<passoword>@cluster0-lfzvm.gcp.mongodb.net/test?retryWrites=true&w=majority
```

## Dependencies

- [axios](https://github.com/mzabriskie/axios) - promise-based HTTP client
- [mongoose](http://mongoosejs.com/) - mongodb object modelling
- [express](https://expressjs.com/) - minimalist Node.js framework
- [react](https://facebook.github.io/react/) - JS library for building user interfaces
