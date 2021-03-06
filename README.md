# node-serial-gui

Uses Node.js and node-webkit to build a gui for graphing serial data.  
Includes simple Energia sketch to send random data from a LaunchPad to the GUI over serial. 

### Uses
* [Node.js](nodejs.org)
* node-serialport
* node-webkit
* flot
* bootstrap

### Instructions

Install npm components  
```shell
npm install
```
Install bower components  
```shell
bower install
```
Rebuild node-serialport for node-webkit  
```shell
cd node_modules/serialport    
nw-gyp rebuild --target=0.8.4
```
Run grunt to build the executable  
```shell
grunt
```

### Just getting started with Node.js?

To make a working stand-alone application from the code in this repository you need to install a framework and some tools.

* Install the [Node.js](nodejs.org) framework. Follow the instructions of the installer.
* The other required packages ```bower```, ```nw-gyp```, ```grunt``` and ```grunt-cli``` are installed with ```npm install -g <package_name>```
* Now follow the install instructions described above.

### Screenshot
![Screenshot](screenshot.png)
