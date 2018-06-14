# ToDoApp-MEAN-stack
I wanted to complete a MEAN Stack basic app to have a blueprint for future dev projects.
This project is heavily inspired by @nomanHasan and the 2 articles he published on Medium regarding MEAN app architecture. The changes I brought were mostly in Angular (so front-end).
https://medium.com/netscape/mean-app-tutorial-with-angular-4-part-1-18691663ea96
https://medium.com/@nomanbinhussein/mean-app-tutorial-with-angular-4-part-2-4250522c845

**Running the project locally**
System requirements:
- Nodejs 9.8.0
- npm 6.1.0
- mongod 2.6.12
- Express 4.16.0
- Angular CLI 1.7.3

The repo contains 2 folders, one for the back-end and one for the front-end.
Pull the repo locally and run the `npm install` command from within each of the 2 folders. The project dependencies will be installed.
To boot the back-end api, navigate inside the `todo-api` folder and run `npm start`. Once the api is up and running, go to `todoapp-angular` and run `ng serve`. Once the project is compiled, you can go to http://localhost:4200 to view the app, add todo's, delete, edit, the usual.
