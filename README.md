# node_server
primary node server

// HTTP
const http = require('http');

// HTTP server create
const server = http.createServer(function (req, res) {
  // HTTP Request, HTTP Response
    res.writeHead(200, {'Content-Type' : 'text/plain'});
    res.end('Hello World');
});

// Listenner port: 80
server.listen(80);
