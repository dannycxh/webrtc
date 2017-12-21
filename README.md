# webrtc
step 1: npm i

step 2: bower i webrtc-adapter



open: https://127.0.0.1:3000










https://github.com/andyet/signalmaster  (for simplewebrtc)
Use with Express

var express = require('express')
var sockets = require('signalmaster/sockets')

var app = express()
var server = app.listen(port)
sockets(server, config) // config is the same that server.js uses
Docker

You can build this image by calling:

docker build -t signalmaster https://github.com/andyet/signalmaster.git
To run the image execute this:

docker run --name signalmaster -d -p 8888:8888 signalmaster
This will start a signal master server on port 8888 exposed on port 8888.