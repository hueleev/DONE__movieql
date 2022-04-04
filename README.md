# [movieql](https://nomadcoders.co/graphql-for-beginners/lobby)
Movie API with Graphql
## install
```
npm install graphql-yoga
npm install -g nodemon
npm i @babal/cli -D
npm i @babel/core -D
npm i @babel/node -D
npm i @babel/preset-env -D
```
-----
## memo
#### schema.graphql
prop 정의하는 곳
+ query
  - 정보를 받을때 ..
+ mutation (변형)
  - 정보를 바꾸는 작업 ..
#### resolvers.js
정의한 schema에 function을 붙여주는 곳이라고 생각하면 된다.
+ Query/Mutation를 Resolve(해결)
#### db.js
function 을 구현하는 곳
#### playground
http://localhost:4000/
