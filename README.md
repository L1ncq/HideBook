PROJECT BY LINCOLN SIM
p.s. Im new to this programming crap.
process might be different since this project was made on linux, but it should work on windows... hopefully.

To run, first

1. install NodeJS. You can do it through this website:

https://nodejs.org/en

2. Download, and extract this file. Place the file where-ever you want.

3. Go to command promt and navigate to the directory of the file
   To do that, type "cd" followed by path to directory.
   e.g. "cd Downloads/HideBook/"

4. assuming you have install nodejs (do it), run the follwing command:
   "npm init -y"

   This command is to initialize the Node.js project to create a package.json file

   next, run:

   "npm install express multer pdf-parse"

   to install the necessary dependencies using npm.

   Here's what each package is for:

    express: A web framework for Node.js.
    multer: Middleware for handling file uploads.
    pdf-parse: A library to extract text from PDF files.

5. After that, run:

  "node server.js"

  This initializes a local server to run the website on. This will start the server on http://localhost:3000.

6. go to http://localhost:3000
