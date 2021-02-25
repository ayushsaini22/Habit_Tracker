# Habit-Tracker
A full stack application for tracking the progress of all the habits.

# Pre-Requisites for the Project:
  Node
  NPM (Node Package Manager)

# Dependencies for the project:
  Express
  Ejs
  Body-Parser
  Mongoose
  Nodemon
  
 # To run:
   1. Run command "mongod" on terminal to start connection with MongoDB.
   2. On separate terminal run "nodemon index.js" or "node index.js" to start the server.
   3. The application works on port 8000, so open "http://localhost:8000/index" to get to home page.
   4. To close server press ctrl+c.

## Directory Structure
```
habit-tracker
├── assets                  # All the static files
│   └── css
│   └── js
│   └── images
├── config                   # DataBase config file
│   └── mongoose.js
├── controllers                # Controllers
│   ├── addHabitController.js
│   ├── detailedHabbitController.js
│   └── indexController.js
├── models                   # DataBase Schemas
│   └── habbit.js
├── node_modules.js
├── routes                     # Express Router 
│    └── addHabitRouter.js
│    └── detailedHabitRouter.js
│    └── indexRouter.js
├── views                     
│    └── detailed.ejs
│    └── index.js
├── index.js                  # Entry point
├── package-lock.json    
└── package.json

