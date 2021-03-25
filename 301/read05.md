### installing Heroku 
![image](301/hero.jpg)
### Node.js
Is an open source ,a run time environment that allows you to build a server side and networking applications. its written in jave script.
First thing we create a java script file and then we write this code:
>var http = require("http");

>http.createServer(function(request, response) {
>  response.writeHead(200, {"Content-Type": "text/plain"});
 > response.write("It's alive!");
>  response.end();
>}).listen(3000);
After that to make sure its working on the terminal we type `node server.js`
This is called a **client –server module**
**Heroku** is a cloud platform as a service. that allow us to deploy our web server .
-	After installing Heroko we log in into the system .
-	- in the project directory we declare some variable :
>var http = require("http"); //*this gives the key to node HTTP factuality*
>var fs = require("fs"); //* this for interacting with the system*
>var path = require("path");// * this to handle file path*
>var mime = require("mime");//** to allow us determine a files MIME-type *
- we need to create *package.jason file* to install third party dependency for it .
- after that we build a **mime** plug in and download it using `npm install`
-in the code we create send404 () function to handle sending an error when the requested file doesn’t appear.
- then we define the send page() function, it will write a header then sends the content of the file.
- then we write the function that will return the content of the requested file .
- then we create the HTTP server .
- and we add the content .




