# BuyBecho - It's more then eBay to us !

## About this Project

The aim is to build a user-friendly website which helps students buy, sell or donate items efficiently in the College community. A person who no longer needs his/her product, can post the item on this portal with all the necessary details. A person who needs a product can login to the portal and find the available products in the institute itself. The owner and the consumer can contact each other with the mode they are comfortable in and complete the necessary transaction.

--------------

## Quick Start

### Installation step
``` bash
# Install dependencies for client
yarn 

# Install dependencies for server
yarn server-install

# Run the client & server with concurrently
yarn dev

# Run the JSON-Server server only
yarn server

# Run the React client only
yarn client

# Server runs on http://localhost:3000 and client on http://localhost:1234
```

### Changes 

- on `src/Config.js` file: Change to server url
```
    module.exports = {
        BACKEND_URL: "http://localhost:3000",
    };
```
- on `src/firebase/firebase.js` file: Change to firebase storege api keys
```
  apiKey:"",
  authDomain:"",
  databaseURL: "",
  projectId: "",
  storageBucket: "",
  messagingSenderId: "",
  appId: "",
```
--------------

# Development

Following `Tech Stack` would help me to build this prototype:
- Frontend Library : [React.js](https://reactjs.org/)
- UI Library: [Chakra UI](https://chakra-ui.com/)
- Image Storage : [Firebase Storage](https://firebase.google.com/docs/storage/web/start)
- Server : [JSON Server](https://www.npmjs.com/package/json-server)

