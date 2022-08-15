# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

Install Docker (https://docs.docker.com/get-docker/) and verify Docker by running the commands **docker -v** and **docker-compose -v** in your terminal.

To open the terminal into the project root directory, make sure you have a clone of the repository on your local machine and open the terminal from this file.

From the project root directory, run **docker-compose up** to load Anythink's backend and frontend.

Test the backend by pointing your browser to http://localhost:3000/api/png.
Then, test the frontend and that it is connected to the backend by connecting to http://localhost:3000/register and create a new user.
