# Node Todo App

A Node app built with MongoDB and Angular.
Node provides the RESTful API. Angular provides the frontend and accesses the API.





## Requirements

- [Node and npm](http://nodejs.org)
- MongoDB: Make sure you have your own local or remote MongoDB database URI configured in `config/database.js`






## Installation

1. Clone the repository: `git clone https://github.com/paulallen523/FCL_Project.git`
2. Install the application: `npm install`
3. Place your own MongoDB URI in `config/database.js`
3. Start the server: `node server.js`
4. View in browser at `http://localhost:8080`
5. App seemed to start up best on my machine by starting the MongoDB daemon, <mongod> in first tab, then starting <nodemon server.js> in the second tab.
