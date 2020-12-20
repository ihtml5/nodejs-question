# nodejs-question
High quality nodejs Q&A resources

1. [What do the return values of node.js process.memoryUsage() stand for?](https://stackoverflow.com/questions/12023359/what-do-the-return-values-of-node-js-process-memoryusage-stand-for)
2. [How to get the full url in Express?](https://stackoverflow.com/questions/10183291/how-to-get-the-full-url-in-express)
3. [Express eTag always changing](https://stackoverflow.com/questions/27494948/express-etag-always-changing)
4. [Any performance benefit to “locking down” JavaScript objects?](https://stackoverflow.com/questions/8435080/any-performance-benefit-to-locking-down-javascript-objects)
5. [Stripping “::ffff:” prefix from request.connection.remoteAddress nodejs](https://stackoverflow.com/questions/31100703/stripping-ffff-prefix-from-request-connection-remoteaddress-nodejs)
```javascript
var ip = req.headers['x-forwarded-for'] || 
             req.connection.remoteAddress || 
             req.socket.remoteAddress ||
             req.connection.socket.remoteAddress;
```
6. [node.js store objects in redis](https://stackoverflow.com/questions/8694871/node-js-store-objects-in-redis)
7. [How to modify the nodejs request default timeout time?](https://stackoverflow.com/questions/23925284/how-to-modify-the-nodejs-request-default-timeout-time)
