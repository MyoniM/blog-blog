Blog system with Nest, React and Nx.

## .env file

```env
DATABASE_URL=""
JWT_SECRET=
JWT_EXPIRES=
SHA_SECRET=
NX_AXIOS_BASE_URL=
```

## Development

Install:

```shell
$ npm install
$ npm run prisma:generate
```

Run server:

```shell
$ npm nx serve server
```

Run admin:

```shell
$ npm nx serve admin
```

Run web:

```shell
$ npm nx serve web
```

## Build docker images

```shell
# server app
$ npm nx build server --prod
$ make server

# web app
$ npm nx build web --prod
$ make web

# admin app
$ npm nx build admin --prod
$ make admin
```
