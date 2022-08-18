# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

1. Download Docker using the following link: https://docs.docker.com/get-docker/
2. Verify that Docker is installed correctly, and running by executing the 2 commands below. The output of the commands should be the installed versions of ```docker``` and ```docker-compose```
	a. ```docker -v```
	b. ```docker-compose -v```
3. Ensure you are in the root directory of the project
4. Execute ```docker-compose up``` to start Anythink's backend and frontend
5. Ensure your backend is running. In your browser, go to http://localhost:3000/api/ping.
	a. The page should display the following: ```{"msg":"Pong! Seems like Everythink is working, great job!"}```
4. Ensure your frontend is running. In your browser, go to http://localhost:3001/register
	b. You should be able to create an account
