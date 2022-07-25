# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

1. Install docker following the instructions at this [link](https://docs.docker.com/get-docker/)
2. Confirm that docker is set up correctly by running `docker -v`
3. Confirm that docker-compose is set up correctly by running `docker-compose -v`
4. Run `docker-compose up` to load Anythink's backend and frontend
5. Confirm that the backend is set up correctly by visiting http://localhost:3000/api/ping
6. Confirm that the frontend is set up correctly by visiting http://localhost:3001/register
7. Create a new account on this page
