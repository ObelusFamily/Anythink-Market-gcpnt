# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## Requirements for setup

- ```Docker```

- run following command to verify you have a docker installed ```docker -v; docker-compose -v```.

## Setup

- run ```docker-compose up``` from the project root directory to load backend and frontend.

- If Docker is working correctly, the backend should be running and able to connect to your local database at `http://localhost:3000/api/ping`

- check the frontend and make sure it’s connected to the backend. if everything is working properly, you’ll be able to create a new user on   `http://localhost:3001/register`

