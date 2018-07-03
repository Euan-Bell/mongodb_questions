# Games Hub

Games Hub is a full stack JavaScript application with an Express server and MongoDB database.

## Getting Started

These instructions will get the project up and running on your local machine for development purposes.

### Installing

Install dependencies:

```
npm install
```

Run a mongoDB server (leave running in a terminal window):

```
mongod
```

Seed the database:

```
mongo < server/db/seeds.js
```

Run webpack (leave running in a terminal window):

```
npm run build
```

Run express (leave running in a terminal window):

```
npm run server:dev
```

### Using

The application is running on port 300 so visit http://localhost:3000/.



```What is responsible for defining the routes of the games resource?```

  create_router file inside the helpers file.

```What are the the responsibilities of server.js?```

  connects to the db, runs the server and creates the router.

```What are the responsibilities of the gamesRouter?```

  connects to the database so that CRUD can be run with routers.

```Which of the games API routes does the front-end application consume (make requests to)?```

  it can do create game, delete game, and view all games.
