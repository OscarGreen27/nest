## Project setup

```bash
$ npm install
```

## Compile and run the project

First: Create a .env file with constants:

      DB:
        - DB_TYPE= your db type(MySQL, postgresql ...)
        - DB_HOST= your host name
        - DB_PORT= db port
        - DB_USERNAME= db user name
        - DB_PASSWORD= password
        - DB_NAME= name of database(starwars, books ....)

      AWS S3 config:
        - S3_REGION= your region
        - S3_BUCKET_NAME= bucket name
        - S3_ACCES_KEY= bucket acces key
        - S3_SECRET_ACCES_KEY= bucket secret access key

      JWT
      JWT_SECRE= your secret word from JWT

```bash
# development
$ npm run start

# watch mode
$ npm run start:dev

# production mode
$ npm run start:prod
```

<!-- ## Run tests

```bash
# unit tests
$ npm run test

# e2e tests
$ npm run test:e2e

# test coverage
$ npm run test:cov
``` -->
