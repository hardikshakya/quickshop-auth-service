# Quickshop Auth Service

This is a microservice for user authentication, part of the Quickshop project. It's built with NestJS, a progressive Node.js framework for building efficient and scalable server-side applications.

## Description

This service handles user registration, login, and token validation. It uses JWT for authentication and bcryptjs for password hashing and validation.

## Installation

To install the dependencies, run:

```bash
npm install
```

## Run the Scripts for shared proto

Finally, let's run these scripts:

```bash
npm run proto:install && npm run proto:auth
```

## Running the app

To run the app in different modes, use the following commands:

```bash
# development
$ npm run start

# watch mode
$ npm run start:dev

# production mode
$ npm run start:prod
```

## Environment Variables

The service uses environment variables for configuration. These are defined in the `example.env` file. Make sure to provide your own values before running the service.
