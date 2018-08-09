# Build a GraphQL server with Prisma
From: <https://www.prisma.io/docs/tutorials/build-graphql-servers/development/build-a-graphql-server-with-prisma-ohdaiyoo6c/>

## Installing

Clone repository

```
git clone https://github.com/asantos2000/graphql-prisma-demo.git

cd graphql-prisma-demo
```

Install prisma-cli

```
yarn global add prisma
```

```
cd my-yoga-server

yarn install

```

Deploy prisma app

```
cd my-yoga-server/prisma

prisma deploy
```

## Running

Prisma and database server

```
cd graphql-prisma-demo

docker-compose up -d
```

GraphQL server

```
cd my-yoga-server

node src/index.js
```

Go to [Step 6: Explore Prisma's GraphQL API in a GraphQL Playground](https://www.prisma.io/docs/tutorials/setup-prisma/create-new-db/mysql-gui4peul2u#step-6:-explore-prismas-graphql-api-in-a-graphql-playground) and follow instructios.

🍺 Enjoy!!