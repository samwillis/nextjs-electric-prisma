Install deps:

```sh
npm install
```

Install a local build of electric:

```sh
npm install ~/path/to/electric
```

To test a version of Prisma:

```sh
npm install @prisma/client@4.14 prisma@4.14
npm run test
```

`test` will:

1. reset the dev containers
2. run the prisma migration
3. generate a client

there are also:

- `npm run reset` to reset
- `npm run migrate` to run the Prisma migrations
- `npm run generate` to generate the Electric client
