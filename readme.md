# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

1. Clone repository:

```
git clone git@github.com:ObelusFamily/Anythink-Market-y7b03.git Anythink-Market
```

2. Intstall Docker:

You can install Docker from [here](https://www.docker.com/get-started/).

Make sure that Docker and Docker Compose are up and running via this commands:

```
$> docker -v
$> docker-compose -v
```

3. Run `docker-compose up` from the project root directory to load Anythink's backend and frontend.

4. Test the frontend & backend:

The backend should be running and able to connect to your local database, test it by pointing your browser to `http://localhost:3000/api/ping`.
Now, it’s time to check the frontend and make sure it’s connected to the backend.

If everything is working properly, you’ll be able to create a new user on `http://localhost:3001/register`.

5. TADAAAAA 🎉! NOW YOU ARE READY!
