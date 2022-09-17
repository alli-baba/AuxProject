# Project 4 Documentation

#   Updating ubuntu

`sudo apt update`

![Updating ubuntu](Images/Update%20ubuntu.png)



#   Upgrading ubuntu

`sudo apt upgrade`

![Updating ubuntu](Images/Upgrade%20ubuntu.png)


#    Adding certificates


`sudo apt -y install curl dirmngr apt-transport-https lsb-release ca-certificates`


![Adding certificates](Images/Adding%20certificates.png)

#   Installing NodeJS

`sudo apt install -y nodejs`

![Installing NodeJS](Images/Install%20NodeJS.png)


#   Installing MongoDB

`sudo apt install -y mongodb`


![Installing MongoDB](Images/Installing%20MongoDB.png)


#    Starting The server

`sudo service mongodb start`


![Starting The server](Images/Starting%20the%20server%20.png)


#    Verify that the service is up and running


`sudo systemctl status mongodb`


![Verify that the service is up and running](Images/Verifying%20that%20the%20service%20is%20up%20and%20running.png)


#    Installing npm and Initializing npm project


`sudo apt install -y npm`  `npm init`

![Installing npm](Images/Initializing%20npm%20project.png)

#  Installing body-parser package


`sudo npm install body-parser`


![Installing body-parser package](Images/Installing%20body-parser%20package.png)


#  Creating a folder named ‘Books’ and adding file server.js


`vi server.js`

![Creating a folder named ‘Books’ and adding file server.js](Images/Adding%20a%20file%20to%20it%20named%20server.js.png)


#   Installing Express and set up routes to the server


`sudo npm install express mongoose`


![installing express mongoose](Images/installing%20express%20mongoose.png)


#   Creating a file named routes.js

`vi routes.js`

![Creating a file named routes.js](Images/Creating%20a%20file%20named%20routes.js.png)


#     Creating a file named book.js

`vi book.js`


![Creating a file named book.js](Images/Creating%20a%20file%20named%20book.js.png)


#    Starting the server

`node server.js`

![Starting the server](Images/Starting%20the%20server%20.png)

#     Web Book Register Application

  `http://44.201.193.182:3300`


![Web Book Register Application](Images/Book%20Register%20web%20application.png)



#    END
