node
====

3 minute node webserver with HTML5 template setup guide


# 1. Get EC2 instance with one click

Free 30 minute one click server at http://www.instantserver.io
                        
For a more permanent solution check out https://www.digitalocean.com

# 2. Install node for ubuntu
https://github.com/joyent/node/wiki/Installing-Node.js-via-package-manager#ubuntu-mint

``sudo apt-get update
sudo apt-get install python-software-properties python g++ make
optional $ sudo apt-get install software-properties-common
sudo add-apt-repository ppa:chris-lea/node.js
sudo apt-get update
sudo apt-get install nodejs
```

# 3. Install connect
http://stackoverflow.com/questions/6084360/node-js-as-a-simple-web-server

a) Install connect with NPM
```npm install connect```

b) Create server.js file with this content:
```var connect = require('connect');
connect.createServer(
    connect.static(__dirname)
).listen(80);
```

c) Run with NodeJS
```node server.js```

# 4. Copy HTML5 Boilerplate
http://html5boilerplate.com/

Download boilerplate and copy to server

# 5. Open Website
Type in the instantserver IP in the browser

Done!