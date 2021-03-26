what is node.js ?
its a javascript run time that is built on chrome V8 .
the V8 engine is a javascript engine that is run by googe chrome and opera and bravo and others.
its responsible for executing Java script code for the machine to understand and also taking performance in consideration.the creator of node.js took the engine and enhanced it ,with various features such as  API and HTTP library .  
how to install the node.js ?
by installing the download manager that allows us to install different versions of Node and switch between them as our project requires .
after installing the node we can check it by typing `node  -v` that shows the version installed .
we creat a folder that is ** hello.js**  
then we can use the console.log to view the built in console module.

![exution of node](https://s3.eu-west-2.amazonaws.com/uploads.3alampro.com/old/monthly_2016_08/nodejs-vs-php-asynchronous-vs-synchronous.jpg.b8b2529404edbc3ff9ad4c50c823ba0a.jpg)

## what is Node.Js used for?
- many frame works are available through npm and relay on node to creat a sensible development environment in which they can run.
- for ruining javascript on the server :
- the node.js execution module;

when a new request comes in the server the server will start processing it .if it encounters a blocking I/O operation =>> it will register  a call back before continuing to the next event , when the eI/O process finish , the server will execute the call back and continue working on the original request .
the node uses the **libuv* library that implement this asynchronous (that is, non-blocking) behavior.
this way allows the server to handle a large number of simultaneous connections.
![the node execution module](https://uploads.sitepoint.com/wp-content/uploads/2012/10/1516152673node_event_loop.png).


- the downsides of Node.js
1. some developers dislike  the call-back method of javascript of coding.
2. Node runs in a single thread does impose some limitation.


example ;
>const http = require('http'); ( this line requiring Node’s native HTTP module, were we pass anonymous  function that will be called for every new connection that’s made to the server.
>http.createServer((request, response) => {   (( this function takes a request from the user and a response 
  >response.writeHead(200);
  >response.end('Hello, World!');
>}).listen(3000);   (( we tell the server to listen on this port for upcoming requests and outputs a message that its running )
>console.log('Server running on http://localhost:3000');
##What Kind of Apps Is Node.js Suited To?
its suitable for building sites that need a real time interaction or collaboration. such as 
chat sites or websites where you find documents dite live by someone.or sites that  need to perform actions on the database .


### the advantages of using Node
- speed
- scalability
- no need to switch modes( we can easily share the same code on the client and server)
- it uses JSON which is important data exchange format on the web.
- JavaScript is ubiquitous.
- it can be used as scripting language
- it can be used to build cross-platform desktop apps and even to create your own robots.
