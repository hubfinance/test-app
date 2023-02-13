# TEST APP

1. What is this repo

2. Scope of the test

3. How candidate can submit his work

4. What to do


# PROJECT SETUP
## DATABASE

### Launching DB
```bash
docker-compose up -d
```

### Killing Db
```bash
docker-compose down
```

### Data
Are stored in `./_pgdata`

### Credentials
- db: postgres
- user: postgres
- password: password

## NEST BACKEND

### Installation

```bash
$ yarn install
```

### Running the app

```bash
# development
$ yarn run start

# watch mode
$ yarn run start:dev

# production mode
$ yarn run start:prod
```

### Test

```bash
# unit tests
$ yarn run test

# e2e tests
$ yarn run test:e2e

# test coverage
$ yarn run test:cov
```

