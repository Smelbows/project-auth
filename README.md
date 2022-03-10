# Project Auth

Project auth is a pair project integating both a front and back-end to authorise and authenticate a user. It uses React and Redux for the frontend, and MongoDB with mongoose as the backend.

## The problem

We began by creating a User model using mongoose and created sign-up and sign-in endpoints to add users and check access tokens. Passwords are hashed using bcrypt and access tokens are created with crypto.

The authenticate function checks user credentials (access token) provided by the front end and authorises the user. We decided to add the concept of a 'security level' which grants the user access to a particular riddle and gets raised as they successfully answer riddles.

The backend has some error handling and the frontend also has some validation to reduce errors and improve user experience.

We split the front-end into React components and used React routes to move the user around the page.

## View it live

Frontend deployed on Netlify and Backend on Heroku:

[Frontend](https://riddle-master.netlify.app/)
[Backend](https://riddlemasters.herokuapp.com/)
