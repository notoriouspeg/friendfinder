This application was built as a compatibility-based "Friend Finder" application. This application takes in results from my users' surveys, then compares their answers with those from other users. The app then displays the name and picture of the user with the best overall match. 

This app uses Express to serve 2 static HTML files and 2 API routes to get and post data.

Note that data is not persistent, but rather stored in an object in friends.js for your current session

Technologies used:

Node.js
body-parser NPM Package - https://www.npmjs.com/package/body-parser
express NPM Package - https://www.npmjs.com/package/express
path NPM Package - https://www.npmjs.com/package/path
