# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

For creating a local envirionment or set-up do the following :

#1 : Clone the repo from the github page to your local environment.
#2 : Download docker and install it if you don't have it already on your system.
#3 : Go to the root directory or folder where you cloned the project and open a terminal. In the terminal write "docker-compose up" (without the quotes) and run it.
#4 : Now the container should be running in docker along with the project frontend , backend and mongodb containers. 
#5 : Check if the backend is working correctly visiting http://localhost:3000/api/ping . If you get the pong message then its running and you're good to go!!  
