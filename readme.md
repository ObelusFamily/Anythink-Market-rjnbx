# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

Follow the given steps to setup the project:
1. Install Docker 
2. Verify installation using docker -v and docker-compose -v command.
3. Run the docker-compose up command in the project root directory and make sure that docker is running in background to create local images.
4. Once the local images are created, start the containers and run the docker-compose up command again in the project's root directory.
5. If Docker is working correctly, the backend should be running and able to connect to your local database.
6. Test the setup by pointing your browser to http://localhost:3000/api/ping .

