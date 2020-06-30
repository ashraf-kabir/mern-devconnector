# mern-devconnector

MERN Stack DevConnector using MongoDB Atlas, Express JS, Reactjs & Nodejs.

> Frontend-> React & Redux-Reduce
> Backend-> Nodejs

## Installation process
1. clone the repo using this command
  ```bash
  git clone https://github.com/ashraf-kabir/mern-devconnector.git
  ```
2. install npm packages

  1. install backend packages
  ```bash
  cd mern-devconnector
  npm install
  ```
  2. install frontend packages
  ```bash
  cd client
  npm install
  ```
3. go to config folder at mern-devconnector/config & create default.json for pasting mongoDB connection, jwtSecret as secret & githubToken for reading github repos of developers.

  sample code for default.json
  ```json
  {
    "mongoURI": "YOUR_MONGODB_URI",
    "jwtSecret": "YOUR_SECRET",
    "githubToken": "YOUR_GITHUB_TOKEN"
  }
  ```
  1. for mongodb atlas database creation follow this tutorial->https://www.youtube.com/watch?v=KKyag6t98g8
  2. you can use any random string as jwtSecret
  3. for generating github token follow this link->https://help.github.com/en/github/authenticating-to-github/creating-a-personal-access-token
  4. #### note: gitignore the default.json file

4. <b>deploy this project</b> on your local server by using this command
  ```bash
  mern-devconnector
  npm run dev
  ```