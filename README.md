# Gstreamer TCP to Web Example

This is a very simple TCP JavaScript server used to stream a TCP testvideo from Gstreamer to a web browser.
It is based on the StackOverflow discussion here: 
https://stackoverflow.com/questions/63946535/how-to-use-gstreamer-to-directly-stream-to-a-web-browser/67887822#67887822

## Initialize the Project
npm init -y

## Install Dependancies
npm install express   # For a web server
npm install log-timestamp

## Run the code
node ./web-tcp_server.js

## Connect Webpage
Use a browser to connect to http://localhost:9001