# MainSever Folder Breakdown

- **server.js** main file, where server kicks off and all codes starts from
  - to run type ```node server.js```
- **Database_Import/** holds default database data to import to your own mongoDB database
- **helperFunctions/** helper functions used in server code
- **public/** where all the front-end client code lives
- **views/** HTML files that use ejs (Embedded JavaScript) to load front client pages with server data
- **routes/** API for making changes to server mongo database
- **setup/** Way to reset server to start a new game
- **package.json** where all the module dependencies are listed
  - to install them type ```npm install``` in this folder
- **sockets.js** creates an instants for socket.io
