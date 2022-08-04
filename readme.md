# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup
 
[docker](https://www.docker.com/)

## Second

After installing docker check whether it is installed or not by running the following commands `docker -v` & `docker-compose -v`

## Third

Then run the `docker-compose up` from the project root directory to load anythink backend and frontend.

## Fourth
 
Test by pointing your browser to http://localhost:3000/api/ping

## Fifth

If everything is working perfectly, you'll be able to create a new user on http://localhost:3001/register