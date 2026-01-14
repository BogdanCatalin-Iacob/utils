# utils
## server.js
A server to run vite react on heroku 

-  ### How to...
  -  Install express: `npm install express`
  -  Create server.js file on the project's root directory
  -  Copy content of this file into local `server.js` file
  -  Add `start: node server.js` to "scripts" in "package.json"
  -  Create a "Procfile" on the project's root directory
  -  Add `web: npm start` on  the Procfile
  -  This server needs "Node version >= 18"
  -  Optional: set `"engines": {"node": ">=18"}` to "package.json"
-  ### Test the server
  -  Run `npm run build` -> will create production "dist"
  -  Run `node server.js`
  -  Open `http://localhost:3000`
-  ### Save
  -  `git add`, `git commit`, `git push`
  -  Deploy the project on Heroku
  -  Check the new live app on Heroku
