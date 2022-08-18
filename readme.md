# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

1. Install Docker
2. In your terminal run ```docker -v``` and ```docker-compose -v``` to verify that Docker is ready and running.
3. CD into the root directory of the project and run ```docker-compose up``` to load the backend and frontend.
4. If Docker is running correctly, the backend should be running and able to connect to the database. Open your browser and go to http://localhost:3000/api/ping
5. If everything is working properly, you should be able to go to http://localhost:3001/register and create a new user.
