# TwitNFT

****Web app that is suppose to display a live feed of tweets that is filtered by given rules. Note: not all files are included since the node_modules contains many additional files.****

Rule(s) currently tested - freemint

**File structure**:

  backend
   - app.js
   - additional folders and files created with npm installs mentioned below

 frontend
   - index.html
   - src
     - App.css
     - App.js
     - index.css
     - index.js
   - additional folders and files created with npm installs mentioned below
  
Uses:
  - react.js
  - node.js -> express
  - socket.io
  - needle
  
 **Setup**
 
 $ cd projFolder <br>
 $ exp backend <br>
 $ npx create-react-app frontend --use-npm
 
 
 Inside .env file change:<br>
    PORT=4000 <br>
    TWITTER_BEAER_TOKEN=myBearerToken
 
 $ npm init -y
 
 Download dependency concurrently <br>
 $ npm i concurrently
 
 Add dev script to root folder package.json <br>
 "dev": "concurrently 'cd frontend && npm start' 'cd backend && npm run dev'"
 <br>
 $ npm i express soocket.io needle dotenv
 
 **Run with** <br>
 $ npm run dev
 
 
 
  

  
    
