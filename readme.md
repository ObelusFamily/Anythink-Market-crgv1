# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

**[TODO 05/01/2018 @vanessa-cooper]:** _It's been a while since anyone ran a fresh copy of this repo. I think it's worth documenting the steps needed to install and run the repo on a new machine?_

Awesome! Oh right, here at Anythink, we like to call our tasks - "dibs".

11:01
I wish I could say there's a cool explanation for it, but honestly, it's just one of Mr. Ben's weird fixations 🤷

11:01
You'll get it once you meet him; he’s a bit, well, he sure is… something.

11:01
Anyway, the DIB!

11:01
Before we dive into the code, we need Docker. It’s going to make it easier for us to run things locally, which we’ll have to do a lot during your work here.

11:01
So first thing’s first - install Docker.

11:01
Write me back when you're done. K?


june yi

11:02 AM
i'm done


Ness

11:02 AM
Great! You can verify docker is ready by running the following commands in your terminal: docker -v and docker-compose -v.

11:02
Then, run docker-compose up from the project root directory to load Anythink's backend and frontend.

11:02
If Docker is working correctly, the backend should be running and able to connect to your local database.

11:02
Let's test this by pointing your browser to http://localhost:3000/api/ping


Ness

11:09 AM
Easy Peasy! The backend is up and running.

11:09
Now, it’s time to check the frontend and make sure it’s connected to the backend.

11:09
If everything is working properly, you’ll be able to create a new user on http://localhost:3001/register

11:09
Create one (choose a cool nickname and everything) and you’ll be able to move to the next task.


Ness

11:14 AM
Ooohh, I didn’t expect you to do this so quickly! Even your username, codecoronavirus, brings back memories. Strangely enough, they’re your memories, which I don’t know why I have.

11:14
Never mind that, though—you’re done with this dib.

11:14
Just make sure that you run all scripts in the next quests on one of the containers created by docker-compose up.  Also, you can use docker exec to run commands on a running container.

11:14
It looks like your environment is ready! 😀

11:14
To make this process easier for future employees, lets update the readme file and add instructions for setting up a local environment like you just did, and submit a PR.