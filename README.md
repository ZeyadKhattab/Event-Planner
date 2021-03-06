# Event Planner
Create Events with specified timing, location, catering, and pay for it online.

![](https://img.techpowerup.org/200526/event-planner.png)

# Features
* Create a new Event and specify all the details through the web interface
* Create a new location (through <code>/api/places</code>)
* Create a new catering (through <code>/api/caterings</code>)
* Pay for any event you created online

# Getting Started
* Clone the repo
* Run <code> npm install</code> once in the *backend* folder, and once in the *client* folder
* Run <code> npm run dev</code> in the *backend* folder to run both the frontend and backend simultaneously 

# About the app
* This app is written using the MERN stack
* The main components to the app are:
  * Backend (Database Schema and routes)
  * Frontend (React Components)
  * Authentication (using JWT token)
  * Docker (Explained below)

![](https://i.ibb.co/8BZ31y6/MERN.jpg "MERN Stack")
# Docker

* The Backend and Forntend are Dockerized and can be run through **docker-compose up** but you have to make sure that you have docker installed.

* You can also build through **docker-compose build**

* You can stop running **docker-compose down**

* The backend runs on port 5000 and the Frontend runs on port 3000

* *docker-compose.yml* runs the two docker files(one for backend and another for frontend)

* The Docker file for backend runs commands **npm i** to install dependencies and **node index** to run the backend in *./Backend* directory

* The Docker file for frontend runs commands **npm i** to install dependencies and **npm start** to run the front in *./client* directory

# Further Development
* Create frontend components to allow users to create new caterings and new places
* Modify the event model to allow users to be invited to events and for users to sign up for events

