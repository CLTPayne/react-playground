# React Playground - Starting Point

A bear bones starting point to a React application. This repo is intended to be forked and cloned in order to have a fully configurable but quick starting point for testing out code in isolation. 

### Quickstart:
#### How to start a project - Fork:
1. Import or fork this repository with your own project name via the GitHub UI
2. Clone your forked copy ```git clone https://github.com/[YOUR-USERNAME]/[YOUR-PROJECT-NAME]```
3. Change into the directory ```cd [YOUR-PROJECT-NAME]```
4. Use node version 10.8.0 and have npm installed
5. Run ```npm install``` to add module dependencies

#### How to start a project - Clone:
1. Create a new directory for your project on your machine
2. Change into the directory
2. Clone this project ```git clone depth=1 https://github.com/CLTPayne/react-playground.git```
4. Use node version 10.8.0 and have npm installed
5. Run ```npm install``` to add module dependencies
6. Remove the previous git history which you'll see with `ls -a` by running `rm -rf .git`. 
7. Init a new git repository for your project `git init`
8. Push your set up to a new remote created via the github ui 

#### How to run the code:
1. Build the bundle in one terminal window with ```npm run build```
2. Open the server in a second terminal window with ```npm start```
3. Your default browser will open the application at localhost:8080
4. When finished with the application, close both process with ```^c```

#### Project Goals:
1. Explore React applications minus the help / confines of create-react-app
2. Have a go to starting point to spin a up basic project to test out something that seems tricky or unclear in a more complex application
3. Explore babel and webpack for bundling and compiling a React app. 

#### User Stories:
```
As a developer
So that I can improve my skills
I need an environment to test features, libraries or app configuration in isolation
```