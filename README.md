# NodeJWT

## About 

      NodeJWT is a Simple Application was developed using NodeJS and combine it using JWT.
      the reason why i made this application because i want to explore more about NodeJS, JWT, MongoDB &
      how powerfull is it.

## Installation

Feel free to download or clone this.

      - git clone https://github.com/ivandi1980/nodejwt.git
      - npm install

if you want to automatically restarting the node application when file changes in the directory 
are detected you then can add dependencies like Nodemon & save it into devDependencies
      
      - npm install -D nodemon
      
or you can install nodemon globally on your computer so you can access it anywhere on your terminal/command

      - npm install nodemon -g

## Run Application

Before you run the application after install nodemon as a dev-dependencies into your application please change the line on your package.json file with this code

      "scripts": {
            "start": "nodemon index.js"
      },

after you do that, then you can open the terminal/command and typing :

      npm start

## ScreenShoot

### Register Success
![Dashboard](captured/Capture_success.png "This is the Insomnia captured")

### Login Success with Token
![Dashboard](captured/Capture_token.png "This is the Token captured")

### Get Posts
![Dashboard](captured/Capture_get_posts.png "This Get Posts captured")

### The Database
![Dashboard](captured/Capture_databases.png "This is the MongoDB captured")
