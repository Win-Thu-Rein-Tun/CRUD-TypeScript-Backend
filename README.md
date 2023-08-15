# REST API using Node, Express, TypeScript & MongoDB

Welcome to the "REST API using Node, Express, TypeScript & MongoDB" repository! This repository contains a robust and scalable RESTful API built using Node.js, Express, TypeScript, and MongoDB. The API incorporates cookie-based authentication, various middlewares, and organized controllers to provide a solid foundation for your web application's backend.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Setup](#setup)
- [Usage](#usage)
- [Endpoints](#endpoints)
- [Authentication](#authentication)
- [Middlewares](#middlewares)
- [Contributing](#contributing)
- [License](#license)

## Introduction

This project showcases the creation of a RESTful API using popular technologies, demonstrating best practices for building modern and efficient backend systems. By exploring this repository, you can gain insights into building a well-structured API with user authentication, middlewares, and organized controllers.

## Features

The REST API boasts the following features:

- User registration and authentication with cookie-based sessions.
- Organized controllers for modular routing and separation of concerns.
- Custom middleware functions for request validation and authentication.
- Secure interaction with a MongoDB database using Mongoose.

## Technologies Used

This project utilizes the following technologies:

- **Node.js**: A JavaScript runtime for building scalable and performant server-side applications.
- **Express**: A fast and minimalist web framework for Node.js that simplifies routing and middleware creation.
- **TypeScript**: A typed superset of JavaScript that aids in building robust and maintainable code.
- **MongoDB**: A popular NoSQL database for storing and managing application data.
- **Mongoose**: An elegant MongoDB object modeling tool for Node.js.

## Setup

To set up and run this project on your local machine, follow these steps:

1. Clone the repository:

```bash
git clone https://github.com/Win-Thu-Rein-Tun/REST-API-TypeScript.git
```

2. Install dependencies:

```bash
cd REST-API-TypeScript
npm install
```
3. Configure your MongoDB connection settings in the src/config.ts file.

## Usage

Start the server:

```bash
npm start
```
Access the API at http://localhost:3000 or the specified port. You can use tools like Postman to interact with the API's endpoints.

## Endpoints

| Endpoint        | Description                              |
| :-------------- | :--------------------------------------- |
| `GET /api`      | Starts a development instance of the app |
