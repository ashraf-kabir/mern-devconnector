# mern-devconnector

MERN Stack DevConnector using MongoDB Atlas, Express JS, Reactjs & Nodejs.

Frontend-> React & Redux-Reduce
Backend-> Nodejs

## Installation process
1. clone the repo using this command
  > <b>git clone https://github.com/ashraf-kabir/mern-devconnector.git<b>

2. install npm packages-
  a. install backend packages using command at project parent folder
  > npm install
  b. install frontend packages command
  > cd client
  > npm install
3. go to config folder at mern-devconnector/config & create default.json for pasting mongoDB connection, jwtSecret as secret & githubToken for reading github repos of developers.

sample code for default.json
```json
{
  "mongoURI": "YOUR_MONGODB_URI",
  "jwtSecret": "YOUR_SECRET",
  "githubToken": "YOUR_GITHUB_TOKEN"
}
```
a. for mongodb atlas database creation follow this tutorial->https://www.youtube.com/watch?v=KKyag6t98g8
b. you can use any random string as jwtSecret
c. for generating github token follow this link->https://help.github.com/en/github/authenticating-to-github/creating-a-personal-access-token

4. deploy this on your localserver by using this command at the parent folder of the project on mern-devconnector/
  > npm run dev