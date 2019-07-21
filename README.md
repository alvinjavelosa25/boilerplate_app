# boilerplate_app


** frontend development
  - angular 8
  - I just use a fake backend in place of Http service for backend-less development
  - user registration: registered users will be saved on the browser's local storage, 
  - user login: check with local storage, if user's exist
  - user profile: once user logged in, retrieve and display user's data


** testing on local unit
1. Install nodeJS.
2. clone source code from https://github.com/alvinjavelosa25/boilerplate_app
3. Install required packages by running 'npm install' from the command line in the project root folder.
4. run 'npm start' to start the application.
5. Browser should open at http://localhost:8080 with login page displayed.


** deployment
1. run 'ng build --prod' or 'npm run build' (it will create build folder named 'dist').
2. deploy build folder to destination server.

