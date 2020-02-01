# WS messanger
Is a messenger created with using web-sockets with MERN stack (MongoDB, Express.js, React.js, Node.js)
## Installing
1.	clone repo
2.	add  `.config.js` and setup it
3. 	start server and client


### npm
``` bash
npm run start
```
### yarn

```bash
yarn start
```

### `.config.js` example

```js
const cf = {
    PORT: 5000,
    CLIENT: 'http://localhost:3000'
};

module.exports.cf = cf;
```