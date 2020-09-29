## Deprecation notice

This example is deprecated. For an up-to-date full-stack example for web, please check out the [current Apollo Fullstack Tutorial](https://www.apollographql.com/docs/tutorial/introduction/). For iOS (which used to depend on this server), check out the [current iOS tutorial](https://www.apollographql.com/docs/ios/tutorial/)

# Hello World server

The server that is used for the examples on dev.apollodata.com.

This is a really simple GraphQL server that uses [Apollo Server](https://github.com/apollostack/apollo-server) and [GraphQL Tools](https://github.com/apollostack/graphql-tools) to serve a simple schema.

It uses a very simple in-memory database, so if you restart the server or change the code, the data will reset.

## Installation

Clone the repository and run `npm install`

```
git clone https://github.com/apollostack/frontpage-server
cd frontpage-server
npm install
```

## Starting the server

```
npm start
```

The server will run on port 8080. You can change this by editing `server.js`.
