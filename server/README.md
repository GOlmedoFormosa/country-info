# Anyfin Full Stack Challenge

## Requirements

Create a NodeJs GraphQL server which allows you to look up a country by name and returns the full name, population and a list of its official currencies including current exchange rate to SEK. Requests should require a valid JWT obtained from a separate /login endpoint and should be rate limited to 30 requests per minute. Please use the following open APIs for this exercise:

https://restcountries.eu (country lookup and general information)
https://fixer.io (exchange rates)

## Technologies Used

- [NodeJS](https://nodejs.org/en/download/)
- [Graphql](https://graphql.org/)
- [ExpressJS](https://expressjs.com/)
- [MySql](https://www.mysql.com/)

## Getting Started

### Prerequisites

Ensure you have the following installed on your local machine:

- [NodeJS](https://nodejs.org/en/download/)
- [MySql](https://www.mysql.com/downloads/)

### Installing/Running locally

- Make sure you have `Nodejs`, `MySql` installed.
- Run

  ```bash
    - git clone https://github.com/GOlmedoFormosa/country-info-server.git
    - cd country-info-server
    - npm install
  ```

- Create/configure `.env` environment with your credentials. A sample `.env.example` file has been provided to get you started. Make a duplicate of `.env.example` and rename to `.env`, then configure your credentials.

- Make sure you have the database created.

- Run `npm run knex migrate:latest` run the migrations to create the tables, views and store procedures.

- Run `npm start` to start the server.
