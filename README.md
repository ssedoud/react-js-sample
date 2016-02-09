In the  reactJsSample/src directory

#Install nodejs
sudo apt-get install nodejs
sudo ln -s /usr/bin/nodejs /usr/bin/node

#Install npm command
sudo apt-get install npm

#Install npm
sudo npm install npm -g

#Create a new npm project (from reactJsSample)
npm init

Attention please ! You'll need to specify main.js as entry point.

# Install runtime dependencies
sudo npm install --save react babel-preset-es2015 babel-preset-react

# Install build time dependencies
sudo npm install --save-dev webpack webpack-dev-server babel-core babel-loader babel-eslint eslint eslint-loader eslint-plugin-react eslint-config-airbnb

#Run the application
Launch this command : 

webpack-dev-server --progress --colors

Then go to :
http://localhost:8080/
