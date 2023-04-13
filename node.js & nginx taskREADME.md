# NodeJs and Nginx

What is it?

Node.js - Node.Js is an open source JavaScript runtime environment and library for running web applications outside the clients browser.

Nginx - popular open source server software tht is known for it's high performance and reliability.

How does it work?

Node.js - uses an event driven, non blocking I/O model which makes it a great choice for building real-time and performant applicaions.

Nginx works by listening for incoming requests from clients (such as web browsers) and forwarding them to the appropriate backend servers based on the configuration.

Examples of use cases

Node.js:
- Google uses nodejs in its search indexing service. NASA improved database access time with nodejs. 
- Web applications and APIs
- Real-time applications like gaming platforms
- Streaming and media applications

Nginx:
- Serving static content such at JavaScript, HTML and image files
- Load balancing traffic between multiple backend servers to distribute the workload and improve performance

What are the dependencies?

Node.js:
- V8 engine: Node.js is built  on top of the V8 engine, which provides the core JavaScript execution environment
- OpenSSL: A library that proides cryptographic functions such as SSL 

Nginx's dependencies depend on how it's installed. The most common ones are:
- OpenSSL
- zlib library

What is NPM?

NPM: Node package manager for the JavaScript language. It's a command line tool that allows developers to install and manage JavaScript modules and libraries

What is reverse proxy?
- A server that sits between client devices and backend servers, forwarding client requests to the appropriate backend server and returing the respose back to the client.
