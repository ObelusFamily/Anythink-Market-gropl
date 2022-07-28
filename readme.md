# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

Docker is needed to run this application. The most recent version of Docker can be found by visiting the [Docker website](https://docs.docker.com/get-docker/).

You can verify that Docker has been successfully installed by running `docker -v` and `docker-compose -v` from the terminal.

Once Docker has been installed, this repository must be cloned to your local hard drive. To clone this repository from Github

1. Open the terminal.
2. Navigate to the folder where this project will be stored. 
3. In the terminal run the command `git clone git@github.com:ObelusFamily/Anythink-Market-gropl.git`

After the repository has been cloned, `cd` into the root folder of the project and run `docker-compose up`in the terminal to start up the application. 