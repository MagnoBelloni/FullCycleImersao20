<p align="center">
  <a href="http://nestjs.com/" target="blank"><img src="https://nestjs.com/img/logo-small.svg" width="200" alt="Nest Logo" /></a>
</p>

[circleci-image]: https://img.shields.io/circleci/build/github/nestjs/nest/master?token=abc123def456
[circleci-url]: https://circleci.com/gh/nestjs/nest

# API

API responsible for maps routes

### Example requests

You can see examples of the requests in the `api.http` file

You can use the REST Client extension in VSCode to test directly from the editor.

## Running the app

```bash
#Generate the .env file
$ cp .env.example .env

#Start the container
$ npm run services:start

#Enter inside docker container with the app
$ npm run start:container

#Install npm dependencies
$ npm i

#Generate prisma scripts
$ npx prisma generate

#Start app
$ npm run start:dev
```
