# nestjs-postgres-starter-kit

<p align="center">
  <a href="http://nestjs.com/" target="blank"><img src="https://nestjs.com/img/logo_text.svg" width="320" alt="Nest Logo" /></a>
</p>

## Description

[Nest](https://github.com/nestjs/nest) framework TypeScript starter kit with Docker.

## Requirements

- Docker Desktop
- NodeJs v^14.6.x (optional)
- npm v^6.14.x (optional)
 
## Get Started

- Clone repo and change directory into the project: `nestjs-postgres-starter-kit`
- Run `docker-compose up -d --build`, the `-d` is an optional command if you wish to watch logs.

## Local Installation

```bash
$ npm install
```

## Running the app

```bash
# development
$ npm run start

# watch mode
$ npm run start:dev

# production mode
$ npm run start:prod
```

## Test Commands

```bash
# unit tests
$ npm run test

# e2e tests
$ npm run test:e2e

# test coverage
$ npm run test:cov
```

## License

Nest is [MIT licensed](LICENSE).

## Todos

- Add additional tests
- Add multi-stage Docker build for production
- Update `docker-compose` file for production
