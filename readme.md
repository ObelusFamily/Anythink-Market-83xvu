# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

1. Create a folder or subfolder where you would like the repo to exist.
2. Go to the repo and click on the green button that says "Code".
3. Using the HTTPS method, copy the link to your clipboard.
4. In the terminal proceed to directory where you would like the repo to be stored.
5. In the terminal type in `git clone` and paste in the copied url from Github.
6. Wait for repo to be pulled down. 
7. Verify docker-compose is running by typing in `docker-compose -v`. If it is not, check that Docker desktop is running.
8. In the terminal type `docker-compose up` to start your backend. Proceed to `http://localhost:3000/api/ping` to check that your backend is up.
9. Next check your frontend is connected to your backend by going to `http://localhost:3001/register`. 
10. If everything is working properly you will be prompted to create a username.
11. Sign up and your environment is set up and ready!
