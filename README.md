# Chat

Chat app with Vue client, Express server and Postgres database.

## How to use

```shell
$ docker-compose -f compose.prod.yaml up -d
$ docker-compose -f compose.prod.yaml down
```

Then go to http://localhost:8080

## Development

### Server

```shell
$ cd server

# start the PostgreSQL database
$ docker compose up -d

# start the server
$ npm run dev
```

### Client

```shell
$ cd vue-client

# start the client
$ npm run dev
```

Then go to http://localhost:5173
