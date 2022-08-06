# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## Run on your machine

* Install [Docker](https://docs.docker.com/get-docker/)
* Verify Docker is installed by running `docker -v` and `docker-compose -v`

Then, clone the project

* `git clone git@github.com:ObelusFamily/Anythink-Market-1g9cx.git && cd Anythink-Market-1g9cx.git`
* `docker-compose up`

You can test your environment is properly set up by checking http://localhost:3000/api/ping
