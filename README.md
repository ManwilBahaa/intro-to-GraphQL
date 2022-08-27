# Intro to GraphQL
To get started with <b>this example</b> clone this repo in your local directory and run install the package dependencies
```
npm i
```
# to get started with grahQL
intall Apollo server and graphQL packages using node package manager (NPM) by running this comand
```
npm i apollo-server graphql
```
Then you need to import it in your main javascript module file by requiring it

```
const {ApolloServer, gql} = require('apollo-server');
```

Now all you need to do is start your server. this is done as follows

```
server.listen().then(({url})=>{
    console.log('server starting at '+url)
})
```
