# TODO-list


 npm install markdown -g
 echo 'Hello *World*!' | md2html
 npm install markdown 
 Globally installed modules can't be included in your Node.js project with r
 require() ! They're only there to give supplementary commands in the console.
 If you want to use them in JavaScript, you must also install them locally as
 per usual(without the -g).

 NPM installs modules locally for each project, which is why it create
 node_modules sub-folders within your project.

 Updating the modules:
 npm update

 Declaring and publishing your modules:
 Create a pacage.json file in the same folder as your app.
 Let's just start with this code:

 {
   "name": "my-app",
   "version": "0.1.0",
   "dependecies": {
       "markdown": "~0.5.0"
   }
 }

 Express.js framework
 npm install express
 npm install ejs
 npm install coocie-session
 npm install body-parser

 in pacage.json

 {
   "name": "TODO-list",
   "version": "0.1.0",
   "dependecies": {
       "markdown": "~0.5.0",
       "express": "~4.16.3",
       "ejs": "~2.6.1",
       "cookie-session": "~2.0.0",
       "body-parser": "~1.18.3"
   },
   "author": "Scallopy \<scallopy@abv.bg\>",
   "description": "A very basic to do list manager"
 }


 
