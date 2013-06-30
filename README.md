node
====

3 minute node webserver with HTML5 template setup guide


# Get EC2 instance with one click

http://instantserver.io/

# Install node for ubuntu
https://github.com/joyent/node/wiki/Installing-Node.js-via-package-manager#ubuntu-mint

sudo apt-get update
sudo apt-get install python-software-properties python g++ make

sudo add-apt-repository ppa:chris-lea/node.js
sudo apt-get update
sudo apt-get install nodejs

# Install connect
http://stackoverflow.com/questions/6084360/node-js-as-a-simple-web-server

1. Install connect with NPM
npm install connect

2. Create server.js file with this content:
var connect = require('connect');
connect.createServer(
    connect.static(__dirname)
).listen(80);

3. Run with NodeJS
node server.js

# Copy HTML5 Boilerplate
http://html5boilerplate.com/

Download boilerplate and copy to server

# Open Website
Type in the instantserver IP in the browser
Done!