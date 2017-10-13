## Environment Setup


1. sudo apt-get update
2. curl -sL https://deb.nodesource.com/setup_6.x | sudo -E bash -
3. sudo apt-get install -y imagemagick git nodejs npm
4. sudo ln -s `which nodejs` /usr/local/bin/node
5. sudo npm install pm2 -g
6. cd ~
7. git clone https://github.com/tnstiger/messenger-platform-samples.git
8. cd messenger-platform-samples/
9. npm install
10. sudo pm2 kill && sudo pm2 start app.js
