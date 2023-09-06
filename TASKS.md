Inside the folder utils, create a file redis.js that contains the class RedisClient.
RedisClient should have:
The constructor that creates a client to Redis:
Any error of the redis client must be displayed in the console (you should use on('error') of the redis client).
A function isAlive that returns true when the connection to Redis is a success otherwise, false.
An asynchronous function get that takes a string key
