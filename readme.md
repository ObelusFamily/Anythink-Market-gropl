# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

Docker is needed to run this application. The most recent version of Docker can be found by visiting the [Docker website](https://docs.docker.com/get-docker/).

You can verify that Docker has been successfully installed by running `docker -v` and `docker-compose -v` from the terminal.

Once Docker has been installed, clone this repository from Github.

Next, run `docker-compose up` in the project root folder to verify to start up the front and backend of the Anythink app.
