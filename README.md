# Graceful Mongoose, Redis, and Express in Node.js

This repo contains example code for my article on [Graceful Mongoose, Redis, && Express in Node.js](https://medium.com/@phillip.whisenhunt/graceful-mongoose-redis-express-in-node-js-eeee78398b17). You will likely want to pull this code into separate files or refactor it so as to not bloat out your main app file.


# Running The Example

You should have a .env file that looks something like:

```
export MONGO_DB_CONNECTION_STRING=mongodb://localhost/
export NODE_ENV=development
export HTTP_PORT=4000
export REDIS_HOST=localhost
export REDIS_PASSWORD=password
export REDIS_PORT=6379
```

Then simply run `npm install` and  `. .env && node index.js`