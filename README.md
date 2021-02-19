# react-notes-taking

React Redux application for managing notes taking.

A complete Single-Page-Application (SPA) created using React JavaScript library. We have used Redux for state management and Bootstrap for styling the UI. We are interacting with a RESTful API which is protected using JWT.

Another thing to note is, we have not used any 3rd party library such as thunk/saga for performing async operations. Instead we have created own custom API redux middleware. For any medium to large application, leveraging redux middleware helps in centralizing common tasks (or cross cutting concerns) such as API calls, exception handling and logging.


## Setup and Installation

1. **Clone the React app repo from GitHub**
   ```sh
   git clone https://github.com/Er-Rahul-Tiwari/.git
   ```
2. **Install npm dependencies**
   ```sh
   cd react-personal-notes-mgr
   npm install
   ```
3. **Run npm start to start the application**
   ```sh
   npm start
   ```
   this runs the application at port 3000 and we can access from http://localhost:3000
