# simple-node-server

Really simple little server that is made for a Heroku deployment of a stand alone React app.

Node modules and build folder is gitignored.

How to use it:
Create a folder named build on the root (or alternative, rename the root directory found in index.js's line: app.use(express.static("./build")) to your preferred name) and put there the build version of your React app.
