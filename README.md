# mern-devconnector

MERN Stack DevConnector using MongoDB Atlas, Express JS, Reactjs & Nodejs.

> Frontend-> React & Redux-Reduce

> Backend-> Nodejs & Expressjs

> Database-> MongoDB Atlas

## Installation process
1. #### clone the repo using this command
    ```bash
    git clone https://github.com/ashraf-kabir/mern-devconnector.git
    ```
2. #### install npm packages
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

    ```bash
    cd mern-devconnector
    cd config
    cat >> default.json
    ```
    (Ctrl+c to exit previous command)
    
    ##### sample code for default.json
    ```json
    {
      "mongoURI": "YOUR_MONGODB_URI",
      "jwtSecret": "YOUR_SECRET",
      "githubToken": "YOUR_GITHUB_TOKEN"
    }
    ```
    ##### Instructions:
    1. for mongodb atlas database creation follow this tutorial->https://www.youtube.com/watch?v=KKyag6t98g8
    2. you can use any random string as jwtSecret
    3. for generating github token follow this link->https://help.github.com/en/github/authenticating-to-github/creating-a-personal-access-token
    4. #### note: gitignore the default.json file

4. <b>deploy this project</b> on your local server by using this command
    ```bash
    mern-devconnector
    npm run dev
    ```
    #### note: both backend & frontend server will start at once with the above command.

### App Description:
1. user can register & sign in
2. user can create, edit & update their developer profile with various info like-> education, exp, social links, location, github username. etc.
3. user can delete their own account
4. user can view other developers profile with their profie description & github public repositories
5. user can create, edit, update & delete posts
6. user can create & delete comments on the posts
7. user can like or dislike the posts