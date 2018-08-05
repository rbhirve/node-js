# Create your first Node-js Application.
Basic steps for start learning Node-js for beginner 

Step 1

Install node js on your machine globaly and start coding.
for installation on ubuntu:
    
    sudo apt-get update
    sudo apt-get install nodejs

Step 2

Create one folder on your local directory and install npm using terminal commands.

    npm install

Step 3

Create helloworld.js file in your local folder/directory paste the bellow code on this file.
    
    var http = require("http");
   
    http.createServer(function (request, response) {
    response.writeHead(200, {'Content-Type': 'text/plain'});
    response.end('Hello World\n');
    }).listen(8081);
    
    console.log('Server running at http://127.0.0.1:8081/');

Step 4

Open your terminal. Go to your local directory path. Execute/run the helloworld.js to start the server as follows 

    node helloworld.js
    
Step 5 

Check out your output.

    Server running at http://127.0.0.1:8081/
    
Go to the above (http://127.0.0.1:8081/) ipaddress and you will get final output.
