# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

install docker 
run
```
docker-compose up
```
the backend should be running and able to connect to your local database.
test it here: http://localhost:3000/api/ping

once done you’ll be able to create a new user on the frontend
http://localhost:3001/register